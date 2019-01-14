# DND For Alfred

To put it simply I wanted a way to tell the world to bugger off so I could get work done. However, its much better when you can time it, so with this you can time your disconnecting from the world.

Once you add the workflow to Alfred, you can use the following command.

```
dnd 45
```

This will enable macOS's DND for 45 minutes. It will output a pleasant notification when the timer runs out.

## Requirements

In order to get this to work right you need to set a keyboard shortcut for `Mission Control`'s `Toggle Do Not Disturb On/Off` option in Keyboard shortcuts. This was needed because AppleScript's key down no longer sustains holding an 'option' key during the execution. To have this work out of the box you need to set the shortcut to `ctrl+space` otherwise, you'll have to customize the AppleScript's running in the Workflow.
