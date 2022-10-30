Proyecto de calidad de software de la universidad Fidélitas del curso calidad de software del grupo 4 
Este proyecto es un sistema que es utilizado para agendar vuelos en una aerolinea ficticia en el cual es necesario tener una cuenta (ya creada en el codigo) para poder agendar un vuelo, en el cual se utilizará Tomcat para identificar los roles del usuario dependiendo de que cuenta se vaya a utilizar de las ya previamente creadas. El proyecto esta en codigo JAVA y utiliza la base de datos Microsoft Access. Las especificaciones masomenos de lo que hace el codigo es lo siguiente:
El administrador de la aerolínea establecerá los precios de los asientos. Debe haber tres tipos de asientos:
Primera clase
Negocio
Economía
El administrador de la aerolínea debería poder crear y actualizar las características de cada tipo de asiento.
El administrador de la aerolínea debería poder establecer el número total de asientos para cada vuelo.
El gerente de la aerolínea debería ver una lista de asientos que el administrador agregó o editó cuando inicia sesión.
El gerente de la aerolínea debe aprobar el nuevo precio o las actualizaciones.
Solo cuando el gerente apruebe el precio y la actualización, entonces debería estar disponible para que el cliente compre.
El Cliente debería poder comprar asientos en función de la disponibilidad.
Cuando un cliente compra un boleto, el sistema debería poder calcular cuántos asientos quedan. Si se compran todos los asientos, la aplicación no debería permitir que los clientes compren más asientos.
El Cliente debe poder seleccionar lo siguiente, para seleccionar un asiento:
ciudades de origen y destino
fechas de viaje
número de personas que viajan
Cuando el cliente selecciona el asiento y confirma la reserva, se debe mostrar el itinerario del vuelo al cliente.
Cuando el cliente aprueba el itinerario, se debe llevar al cliente a una página de pago donde se debe mostrar el precio total. Cuando el cliente presione el botón de pago, considere la transacción realizada y marque el asiento vendido.
Una vez vendido el asiento, envíe un correo electrónico al cliente con el itinerario del vuelo.
