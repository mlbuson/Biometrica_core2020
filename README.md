# Autenticación Biométrica Core
 
Desarrollo de prototipo de módulo web en el que los usuarios pueden ser identificados por reconocimiento biométrico (facial y de voz).

## Autor
* **Lautaro buson** - [MLBUSON]    (https://github.com/mlbuson/Biometrica_core2020)

## Introducción

En el presente proyecto se va a trabajar específicamente con biometría facial y de voz, características que nos permiten reconocer a alguien sin el uso de algún sensor especial y que pueden ser utilizadas en la mayoría de los teléfonos y computadoras actuales, esto con el fin de hacer más fácil su uso e instalación y así poder ampliar el campo de aplicación de la herramienta

* [Amazon Web Services](https://aws.amazon.com/es/)

Es necesario crear una cuenta, inicialmente se otorga un año en la capa gratuita la cual incluye Amazon Rekognition, el cual es el servicio de reconocimiento facial, en el siguiente link esta la información para generar las credenciales [Amazon Rekognition](https://aws.amazon.com/es/rekognition/getting-started/).

* [VoiceIT](https://voiceit.io/)

Es necesario crear una cuenta, inicialmente se otorga un mes de prueba gratuita del servicio de reconocimiento de voz, una vez realizado el registro se genera automáticamente las credenciales para su uso.

### Instalación

Basta con clonar o copiar el repositorio en un servidor local y configurar dos archivos con las credenciales.

Para validar los servicios de reconocimiento facial en la carpeta App se encuentra el archivo **config.php**, se deben cambiar las siguientes variables de acuerdo a la configuración que se tenga en aws.


## Desarrollado con:

* [Amazon Rekognition](https://aws.amazon.com/es/) - Reconocimiento Facial
* [VoiceIt](https://voiceit.io/) - Reconocimiento de voz
* [Materialize](http://materializecss.com/) - Front-end framework
* [Sweet Alert 2](https://limonte.github.io/sweetalert2/) - Alertas dinámicas en JavaScript
