# Diccionario de Datos — DataCo Smart Supply Chain

Dataset original: [DataCo Smart Supply Chain for Big Data Analysis (Kaggle)](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

| Columna | Descripción |
|---|---|
| Type | Tipo de transacción realizada |
| Days for shipping (real) | Días reales de envío del producto comprado |
| Days for shipment (scheduled) | Días programados de entrega del producto comprado |
| Benefit per order | Ganancia por pedido realizado |
| Sales per customer | Ventas totales por cliente |
| Delivery Status | Estado de entrega: Advance shipping, Late delivery, Shipping canceled, Shipping on time |
| Late_delivery_risk | Variable categórica que indica si el envío está retrasado (1) o no (0) |
| Category Id | Código de categoría del producto |
| Category Name | Descripción de la categoría del producto |
| Customer City | Ciudad donde el cliente realizó la compra |
| Customer Country | País donde el cliente realizó la compra |
| Customer Email | Correo del cliente |
| Customer Fname | Nombre del cliente |
| Customer Id | ID del cliente |
| Customer Lname | Apellido del cliente |
| Customer Password | Clave enmascarada del cliente |
| Customer Segment | Tipo de cliente: Consumer, Corporate, Home Office |
| Customer State | Estado al que pertenece la tienda donde se registró la compra |
| Customer Street | Calle a la que pertenece la tienda donde se registró la compra |
| Customer Zipcode | Código postal del cliente |
| Department Id | Código de departamento de la tienda |
| Department Name | Nombre del departamento de la tienda |
| Latitude | Latitud correspondiente a la ubicación de la tienda |
| Longitude | Longitud correspondiente a la ubicación de la tienda |
| Market | Mercado al que se entrega el pedido: Africa, Europe, LATAM, Pacific Asia, USCA |
| Order City | Ciudad de destino del pedido |
| Order Country | País de destino del pedido |
| Order Customer Id | Código de cliente del pedido |
| order date (DateOrders) | Fecha en que se realiza el pedido |
| Order Id | Código del pedido |
| Order Item Cardprod Id | Código de producto generado por lector RFID |
| Order Item Discount | Valor de descuento del ítem del pedido |
| Order Item Discount Rate | Porcentaje de descuento del ítem del pedido |
| Order Item Id | Código del ítem del pedido |
| Order Item Product Price | Precio del producto sin descuento |
| Order Item Profit Ratio | Ratio de rentabilidad del ítem del pedido |
| Order Item Quantity | Cantidad de productos por pedido |
| Sales | Valor en ventas |
| Order Item Total | Monto total por pedido |
| Order Profit Per Order | Ganancia por pedido |
| Order Region | Región del mundo a la que se entrega el pedido |
| Order State | Estado de la región a la que se entrega el pedido |
| Order Status | Estado del pedido: COMPLETE, PENDING, CLOSED, PENDING_PAYMENT, CANCELED, PROCESSING, SUSPECTED_FRAUD, ON_HOLD, PAYMENT_REVIEW |
| Product Card Id | Código del producto |
| Product Category Id | Código de categoría del producto |
| Product Description | Descripción del producto (vacía en la totalidad del dataset) |
| Product Image | Enlace de visita y compra del producto |
| Product Name | Nombre del producto |
| Product Price | Precio del producto |
| Product Status | Estado del stock del producto: 1 no disponible, 0 disponible |
| Shipping date (DateOrders) | Fecha y hora exacta del envío |
| Shipping Mode | Modalidad de envío: Standard Class, First Class, Second Class, Same Day |

> **Nota:** el dataset original contiene una columna adicional, `Order Zipcode`, que no fue documentada en el diccionario oficial de Kaggle. Se mantiene fuera de este diccionario y del modelo dimensional por consistencia con la fuente oficial.