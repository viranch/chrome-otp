# chrome-otp
Chrome extension to automatically type/paste OTP on web pages

## Usage
Set account name in the format `<Name>::<URL>::<name attribute of input element>`. For eg: `My web::https://example.com/2fa::code`. When the specified URL is opened, the extension will generate OTP, copy it to clipboard, and put it in the text input if there's one matching the with the name mentioned.
