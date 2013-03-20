yandex-translate
================

[Yandex.Translate](http://api.yandex.com/translate/doc/dg/concepts/api-overview.xml) API client for node.js

```js
var translate = require('yandex-translate');
translate('You can burn my house, steal my car, drink my liquor from an old fruitjar.', { to: 'ru' }, function(err, res) {
  console.log(res.text);
});

translate.detect('Граждане Российской Федерации имеют право собираться мирно без оружия, проводить собрания, митинги и демонстрации, шествия и пикетирование', function(err, res) {
   // res.lang -> 'ru'
});
```

# License
MIT.

Yandex.Translate terms of service: http://legal.yandex.com/translate_api/

# See also
[Google Translate client](https://github.com/Marak/translate.js) by @marak

