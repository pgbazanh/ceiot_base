# Ejercicio CiberKillChain - Ataque

Haga una copia de este documto

## Alumno

Paolo Bazán Hernández

## Enunciado

Armar una cyberkillchain usando técnicas de la matriz de Att&ck para un escenario relacionado a tu trabajo práctico

Se muestra a continuación las fases de la matriz de ataque de CyberKillChain.

[image desc](img/ckc1.png)


## Datos trabajo práctico

Habiendo conocido el modelo de Cyber Kill Chain, este será aplicado a mi trabajo práctico, el cual describo a continuación

Título de trabajo práctico: Sistema de Monitoreo inteligente del consumo de agua.

Objetivo

Permitir la lectura del caudal o flujo de agua en puntos en la red de agua potable de una
casa, condominio o empresa con la finalidad de poder detectar fugas de agua y poder tomar
acción correctiva de reparación, permitiendo principalmente ahorro del recurso hídrico y
colateralmente, de dinero.

El trabajo práctico se abordará con un sensor inalámbrico de caudal de agua que permita
la lectura del caudal que pasa por el punto monitoreado. Los datos deberán ser enviados a
través de un broker MQTT, para su almacenamiento en una base de datos. En el frente de
visualización de la información, se propone la creación de aplicación que permita mostrar el
flujo de agua en el punto monitoreado, así como su consumo acumulado durante un tiempo
definido. En la figura, se muestra diagrama ilustrativo de la solución

[label](PB_E1_Ciberkillchain_ataque.md)

En la capa de sensorización, se necesitará de un dispositivo que permita capturar el caudal
en tiempo real del agua que pasa por un punto específico. Este dispositivo deberá ser capaz
de enviar el dato de forma inalámbrica al servicio de Broker MQTT.
La conectividad del dispositivo, para el trabajo propuesto, deberá ser de tipo WiFi, que
podría aplicarse también en una red doméstica o empresa pequeña.
En la capa middleware, los servicios de broker MQTT, servirán para concentrar los datos
enviados por los sensores. Estos podrían ser alojados por un servicio de nube o de forma
on premise.
Los datos procesados inicialmente por el broker MQTT deberán ser almacenados en un
servicio de repositorio que permita la guardar la siguiente información:
● ID del dispositivo
● Fecha y hora de captura
● Dato del caudal detectado
El aplicativo alojado en un servicio de nube, tendrá como objetivo básico mostrar:
● Caudal en tiempo real del sensor desplegado
● Caudal acumulado en un periodo definido
Opcionalmente, se podría complementar con mayor información o inteligencia, que permita
comparar información histórica en un periodo anterior, con el fin de alertar de posibles
anomalías en el consumo.

## Resolución
