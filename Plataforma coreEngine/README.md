# Plataforma coreEngine
Plataforma Básica enfocada al manejo e interacción con los distintos módulos instalados, algunos independientes de otros, y otros dependientes de la instalación de otros módulos

### Demo Plataforma
URL Demo: [democliente.simplivet.cl](https://democliente.simplivet.cl/)<br/>
Usuario: demo1@testmail.com<br/>
Contraseña: 1234

### Caracteristicas
#### Funcionalidades de la plataforma
#### - Core
Base funcional de la plataforma

##### Login
Pantalla de inicio sesión y recuperación de contraseña

<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_1.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_2.jpg' />

##### Principal
Pantalla principal al iniciar Sesión

<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_3.jpg' />

##### Perfil
<p>Sección de modificacion datos del perfil del usuario logueado</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_4.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_5.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_6.jpg' />

##### Plataforma - Pruebas
<p>Apartado para hacer pruebas y testeos de la plataforma</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_7.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_8.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_9.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_10.jpg' />

##### Plataforma - Componentes
<p>Listado de los componentes para las distintas funciones</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_11.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_12.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_13.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_14.jpg' />

##### Plataforma - Administración
<p>Sección para la administración de la plataforma</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_15.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_16.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_17.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_18.jpg' />

#### - Gestión usuarios:
<p>Módulo instalado por defecto que permite la gestión, asignación de permisos y sus niveles de acceso a los distintos módulos instalados</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_19.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_20.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_21.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_22.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_23.jpg' />

#### - Gestión de proyectos:
<p>Módulo de proyectos utilizando un tablero kanban. Permite la creación y administración de las tareas dentro del tablero kanban. También permite la creación y administración de cada etapa de los proyectos, también permite la configuración de las tareas internas de cada tarea ingresada, permitiendo la utilización de solo descripciones o la utilización de tareas predeterminadas configuradas en otra transacción separada.</p>
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_24.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_25.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_26.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_27.jpg' />
<img src='https://github.com/tenshi98/Trabajo_Imagenes/blob/main/Plataforma%20coreEngine/src/img_28.jpg' />

#### - Gestión documentos mercantiles:
<p>Módulo que permite el ingreso de documentos mercantiles tales como ordenes de compra, guías de despacho, facturas, notas de crédito y débito, también permite la administración de sus estados de pago. Se puede configurar para que trabaje en conjunto con el modulo Gestión Bodegas y Productos para registrar el ingreso/salida de productos a las distintas bodegas de la empresa. También permite la interacción con el SII mediante el uso de un servicio externo Libre DTE utilizando su API.</p>

#### - Gestión Bodegas y Productos:
<p>Módulo que permite el manejo de stock, el ingreso/egreso y el movimiento de productos entre las distintas bodegas administradas</p>

#### - Gestión Mantenciones:
<p>Módulo que permite el manejo de las mantenciones de las distintas maquinas al interior de las empresas, gestionando sus mantenciones preventivas, de urgencia y los análisis de las maquinas que lo requieran. Requiere del modulo Gestión Máquinas, Gestión Entidades y Gestión Ubicaciones para funcionar (para identificar la máquina que se le va a hacer mantenimiento, la ubicación de esta al interior de la empresa y las personas encargadas de hacer los mantenimientos), de forma alternativa se puede hacer uso del Módulo Gestión Bodegas y Productos para llevar un detalle de los productos utilizados en cada mantenimiento</p>

#### - Gestión Entidades:
<p>Módulo enfocado en la gestión de personas/empresas, sus contactos, observaciones ingresadas, etc. Es un modulo cuya función es ser utilizado por los demás módulos</p>

#### - Gestión Vendedores:
<p>Módulo enfocado a la captación de prospectos de clientes y la fidelización de estos, hace uso del modulo Gestión Entidades. Si esta en uso el modulo de Gestión documentos mercantiles también lleva los KPI de ventas generadas</p>

#### - Gestión Máquinas:
<p>Módulo que permite la administración de los distintos equipos o maquinas dentro de la empresa</p>

#### - Gestión Ubicaciones:
<p>Módulo que permite la gestión de las ubicaciones al interior de la empresa</p>

#### - Gestión Producción:
<p>Módulo enfocado a la gestión de tiempos en el proceso productivo de las empresas, permite llevar un registro de los tiempos de preparación, producción y tiempos muertos de cada orden de fabricación de la empresa, para asi ofrecer mediante KPI distintas soluciones a los tiempos muertos que son el principal factor en las perdidas y disminución de la productividad</p>

#### - Gestión R.R.H.H.:
<p>Módulo enfocado en la gestión del personal al interior de las empresas, permite entre otras cosas la gestión de trabajadores, la gestión de cargas, la facturación de sueldo, la gestión de anticipos de sueldo, la asignación de bonos fijos y temporales, la gestión de las cartas de amonestación, la gestión de los descuentos por prestamos, la gestión de las horas extras, la gestión de las inasistencias, etc.</p>



---

[Volver al Repositorio](https://github.com/tenshi98/Trabajo_Imagenes/)

---

## Licencia 📄
Este proyecto está bajo la Licencia GPL-3.0 license - ve el archivo [LICENSE](LICENSE) para detalles

## Contacto 📖
Puedes contactarte conmigo a través de cualquier de los siguientes canales:
- [Github](https://github.com/tenshi98)
- [Linkedin](https://www.linkedin.com/in/victor-reyes-galvez/)
- [Portafolio](https://tenshi98.github.io/portafolio/)
- [Mi Web](https://web.digitalcreations.cl/)

## Contribuciones 🎁
Si encontraste cualquier valor en este proyecto o quieres contribuir, aquí está lo que puedes hacer:

- Comparte este proyecto con otros.
- Invítame un café ☕.
- Inicia un nuevo problema o contribuye con un PR.
- Muestra tu agradecimiento diciendo gracias en un nuevo problema.

---

⌨️ por [Víctor Reyes](https://github.com/tenshi98) 😊