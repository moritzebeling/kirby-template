# Custom Kirby Starterkit
Quickstart an new website using Kirby CMS on a PHP server

## Kirby
- [Kirby GitHub](https://github.com/getkirby)
- [Kirby Website](https://getkirby.com)
- [Kirby Reference](http://getkirby.com/docs/reference)
- [Kirby Forum](https://forum.getkirby.com)
- [This Starterkit template](https://github.com/moritzebeling/kirby-starterkit)

## Start
Click `Use this template` to create a new repo from this template, then:
```
git clone --recursive {https://github.com/user/repo.git}
cd {repo}
```
If you need to re-add kirby as submodule:
```
git submodule add https://github.com/getkirby/kirby kirby
```
To run the page on a PHP server:
```
php -S localhost:8000 kirby/router.php
```

## Stack
- VS Code
- [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
```json
    // VS Code settings.json for Live Sass Compiler
    "liveSassCompile.settings.formats":[
        {
            "format": "compressed",
            "extensionName": ".css",
            "savePath": "~/../css/"
        }
    ],
    "liveSassCompile.settings.includeItems": [
        "assets/scss/*.scss"
    ],
    "liveSassCompile.settings.excludeList": [ 
        "**/node_modules/**",
        ".vscode/**" ,
        "kirby/**"
    ],
    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 2 versions"
    ]
}
```

## License
This is just a custom edit of the official [Kirby Starterkit](https://github.com/getkirby/starterkit). [Buy](https://getkirby.com/buy) a license or read the [aggreement](https://getkirby.com/license).