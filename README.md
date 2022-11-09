# Base64 Converter Tool
A simple tool that can convert any file into a base64 string

You can find it online here: https://www.antoineguedes.com/base64converter/

## How-to
* Select the file you want to convert using the input above;
* Open your browser developer tools: Windows: ctrl + alt + i; Mac: option + cmd + i;
* Open the 'Console' tab;
* Copy the base64 code shown in the console;
* Paste the base64 code into your file (see examples below);

## Examples
Background image:

```
.classsname {
    background-image: url('[copied base64 code]');
}
```

Source image:
```
<img src="[copied base64 code]">
```

Web font:
```
@font-face {
    font-family: '[font name]';
    src: url('[copied base64 code]');
    font-weight: [font-weight value];
    font-style: [font-weight style];
}
```

This online tool was created by Antoine Guédès on Nov 9, 2022.
Feel free to use it or redistribute it for any kind of your projects — personal or commercial.
If you have questions or would like to suggest something, you can drop me a line at antoineguds[at]gmail.com
