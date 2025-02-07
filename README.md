# AutoHotkey: macro and automation Windows scripting language.

If you need to automate windows, [AutoHotkey](https://www.autohotkey.com/) has a full scripting language that allows programming complex macros.

Here’s an example.

```
^!s:: // Ctrl+Alt+S becomes a hotkey to type a signature:
Send Sincerely,{Enter}John Smith
return

::btw::by the way // expands to "by the way" when "btw" is typed
```
