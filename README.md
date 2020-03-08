# UNQ » UIs » Web » Login & Beers

Construcción de Interfaces de Usuario, Universidad Nacional de Quilmes.

## Download

```sh
git clone https://github.com/unq-ui/ej-web-login-and-beers.git
cd ej-web-login-and-beers
npm install
```

## Run

```sh
npm start
```

## Creando desde cero

## Parte 1

Crear el proyecto con el comando `create-react-app`

```sh
npx create-react-app MY-APP-NAME
```

## Parte 2

Agregar dependencias útiles

* bootstrap
* jquery (dependencia para bootstrap)
* popper.js (dependencia para bootstrap)
* react-router-dom (para hacer routeo) (Parte 4)
* axios (para realiar requests) (Parte 5)

```sh
npm install bootstrap jquery popper.js react-router-dom axios
```

## Parte 3

Crear el componente `Login` con dos inputs (_usuario_ y _password_) y un botón para autenticarse.
Para este ejemplo el chequeo es local y la info de usuario
está _harcodeada_ en el código por simplicidad didáctica, pero no es una buena práctica.

**Login:**

usuario: _juan_
contraseña: _juan_

## Parte 4

Crear el componente `Home` para que después de hacer _click_ y que
el login sea correcto, se pueda redireccionar a ese componente.

## Parte 5

En `Home` realizar un pedido a la api publica `https://api.punkapi.com/v2/beers`
y listar los resultados.
