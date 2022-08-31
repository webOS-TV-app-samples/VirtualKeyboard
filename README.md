# Virtual Keyboard

webOS TV provides the system keyboard which is automatically displayed on the webOS TV screen if you let your cursor in
the text window. The system keyboard is called the virtual keyboard for webOS TV. The virtual keyboard is the primary
text input method for the webOSTV app, and you can customize it as the following types.

- Text (Default)
- Number
- E-mail
- URL

To check the UI of each virtual keyboard type,
see [Virtual Keyboard](https://webostv.developer.lge.com/develop/guides/virtual-keyboard).

## Setting the Input Type for the Virtual Keyboard

Before starting to use the virtual keyboards, you should know that the virtual keyboard is always enabled and cannot be
disabled. To set the virtual keyboard on webOS TV as you want, add the HTML5 input tag as below.

```html
<form>
  <input type="”text”" />
  <input type="”number”" />
  <input type="”email”" />
  <input type="”url”" />
</form>
```

## Do’s and Don’ts

- **Do** test this sample app on your webOS TV emulator and real webOS TV.

- **Don’t** test this sample app on your PC browser because it is impossible to see the webOS TV virtual keyboard on the
  browser.
