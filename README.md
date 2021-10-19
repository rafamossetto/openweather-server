# Ip-Api + OpenWeather server

Challenge tecnico

## Instalacion

Use the package manager [npm](https://www.npmjs.com/)

```bash
# (En el directorio del repositorio)
npm install 
npm start
# Para correr los tests
npm test
```

## Instrucciones

```python
El servidor tiene cargadas 5 ciudades para probarse (texas, chicago, kansas, florida y manhattan)
estos se pueden ver en el archivo 'data.js'

# GET a /location
Nos devuelve la informacion de Ip-Api de nuestra ubicacion

# GET a /location?city=[city]
Nos devuelve la informacion de Ip-Api de la ciudad pasada por query, de las ya mencionadas arriba

# GET a /current
Nos devuelve la informacion de Ip-Api de nuestra ubicacion y del clima actual segun OpenWeather

# GET a /current[/city]
Nos devuelve la informacion de Ip-Api de la ciudad pasada por params y del clima actual segun OpenWeather

# GET a /forecast
Nos devuelve la informacion de Ip-Api de nuestra ubicacion y estado del clima a 5 dias segun OpenWeather

# GET a /forecast[/city]
Nos devuelve la informacion de Ip-Api de la ciudad pasada por params y del estado del clima a 5 dias segun OpenWeather
```
```
Nota: se incluyo el archivo .env con la Api Key de OpenWeather para poder probar el server correctamente
```
