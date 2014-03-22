*This repository is a mirror of the [component](http://component.io) module [jaycetde/serialize](http://github.com/jaycetde/serialize). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jaycetde-serialize`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# serialize

  Serialize forms into JSON object

## Installation

    $ component install JayceTDE/serialize

## API

```html
<form id="form">
    <input type="text" name="username" value="USERNAME" />
    <input type="password" name="password" value="PASSWORD" />
    <input type="submit" />
</form>
```

```javascript
var serialize = require('serialize')
  , form = document.querySelector('#form')
;

serialize(form); // { username: "USERNAME", password: "PASSWORD" }
```

## License

  MIT
