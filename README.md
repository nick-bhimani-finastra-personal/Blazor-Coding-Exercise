## Scenario

You are working on an existing **Settings** page in a Blazor application. Your task is to add the following features to the settings page.

## Requirements

1. **Feature Counter**  
   Add a counter at the top of the feature flag list that displays the number of enabled features.

2. **Advanced Settings Toggle**  
   If **Advanced Settings** is checked, the advanced settings section must appear on the main settings page.  
   This behavior is triggered by calling OnShowAdvancedSettingsChanged(bool enabled)

3. **Dependent Feature Behavior**  
If **Advanced Settings** is enabled, the checkbox for **Beta Search** must be disabled.

4. **Component Integration**  
Add the **Feature Flag List** component to the Settings page.

