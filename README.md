# Payments
Repositorio de pago, testing

--Para poder correr el siguiente codigo, se necesitan las librerias de mercadopago/dx manejadas en composer
-Instalacion de composer 

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '756890a4488ce9024fc62c56153228907f1545c228516cbf63f885e036d37e9a59d27d63f46af1d4d07ee0f76181c7d3') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"

-Checkout API Pro
https://www.mercadopago.com.ar/developers/es/guides/online-payments/checkout-pro/integration
