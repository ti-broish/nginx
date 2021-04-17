<p align="center">
  <img align="center" src="https://tibroish.bg/brand/youCount_horizontal_RGB_black.png" alt="Ти Броиш лого" width="500px">
</p>

<h1 align="center">Ти Броиш Nginx Конфигурация</h1>

Ти Броиш е платформа за паралелно преброяване и проследяване на парламентарните избори в България.

Това е примерна Nginx конфигурация за reverse proxy na сървъра на [Ти Броиш API](https://github.com/ti-broish/api).

## Конфигурация

- Nginx служи като reverse proxy, което слуша на портове 80 и 443 и предава заявките към Node.js на определен порт.
- Nginx конфигурацията е предимно генерирана от [Nginx генератор на Digital Ocean](https://www.digitalocean.com/community/tools/nginx)
- Има [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) поддржъжка, която по избор може да се включи, ако приложението не предлага CORS headers.


## Контакти

- [team@tibroish.bg](mailto:team@tibroish.bg)

## Лиценз

Кодът на Ти Броиш е лицензиран под [MIT лиценз](https://github.com/ti-broosh/nginx/blob/master/LICENSE).
