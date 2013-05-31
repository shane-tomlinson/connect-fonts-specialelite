# connect-fonts-specialelite

Special Elite fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-specialelite");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/specialelite/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* specialelite

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/specialelite/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* en

5. Set your CSS up to use the new font by using the "Special Elite" font-family.
```
    body {
      font-family: 'Special Elite', 'sans-serif', 'serif';
    }
```

## Font Info
Special Elite

* Description: Copyright (c) 2010 by Brian J. Bonislawsky DBA Astigmatic (AOETI). All rights reserved. Available under the Apache 2.0 licence.http://www.apache.org/licenses/LICENSE-2.0.html
* Copyright: Copyright (c) 2010 by Brian J. Bonislawsky DBA Astigmatic (AOETI). All rights reserved. Available under the Apache 2.0 licence.http://www.apache.org/licenses/LICENSE-2.0.html
* Trademark: Special Elite is a trademark of Astigmatic (AOETI).
* Designer: Astigmatic (AOETI)
* Designer URL: http://www.astigmatic.com/ 
* Vendor: Astigmatic (AOETI)
* Vendor URL: http://www.astigmatic.com/

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-specialelite
* Repo: https://github.com/shane-tomlinson/connect-fonts-specialelite

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 2.0 of the Apache

  http://www.apache.org/licenses/LICENSE-2.0

