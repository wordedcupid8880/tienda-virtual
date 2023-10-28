# tienda-virtual
class Proveedor:
    def __init__(self, id_proveedor, nombre, documento, direccion, correo, telefono):
        self.id_proveedor = id_proveedor
        self.nombre = nombre
        self.documento = documento
        self.direccion = direccion
        self.correo = correo
        self.telefono = telefono

    def ingresar(self):
        # Implementar la lógica para ingresar un proveedor
        pass

    def modificar(self):
        # Implementar la lógica para modificar un proveedor
        pass

    def consultar(self):
        # Implementar la lógica para consultar un proveedor
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar un proveedor
        pass
class Articulo:
    def __init__(self, id_articulo, nombre, marca, referencia, id_proveedor, stock):
        self.id_articulo = id_articulo
        self.nombre = nombre
        self.marca = marca
        self.referencia = referencia
        self.id_proveedor = id_proveedor
        self.stock = stock

    def ingresar(self):
        # Implementar la lógica para ingresar un artículo
        pass

    def adicionar(self):
        # Implementar la lógica para adicionar stock a un artículo
        pass

    def modificar(self):
        # Implementar la lógica para modificar un artículo
        pass

    def consultar(self):
        # Implementar la lógica para consultar un artículo
        pass

    def validarproveedor(self):
        # Implementar la lógica para validar el proveedor de un artículo
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar un artículo
        pass
class Salida:
    def __init__(self, id_salida, cantidad, valor_unidad, fecha, id_articulo):
        self.id_salida = id_salida
        self.cantidad = cantidad
        self.valor_unidad = valor_unidad
        self.fecha = fecha
        self.id_articulo = id_articulo

    def ingresar(self):
        # Implementar la lógica para ingresar una salida
        pass

    def modificar(self):
        # Implementar la lógica para modificar una salida
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar una salida
        pass

    def consultar(self):
        # Implementar la lógica para consultar una salida
        pass

    def validar_codigo(self):
        # Implementar la lógica para validar el código de una salida
        pass
class Entrada:
    def __init__(self, id_entrada, valor_unidad, fecha, factura, cantidad, id_articulo):
        self.id_entrada = id_entrada
        self.valor_unidad = valor_unidad
        self.fecha = fecha
        self.factura = factura
        self.cantidad = cantidad
        self.id_articulo = id_articulo

    def ingresar(self):
        # Implementar la lógica para ingresar una entrada
        pass

    def modificar(self):
        # Implementar la lógica para modificar una entrada
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar una entrada
        pass

    def consultar(self):
        # Implementar la lógica para consultar una entrada
        pass

    def validar_articulo(self):
        # Implementar la lógica para validar el artículo de una entrada
        pass
class Devolucion:
    def __init__(self, id_devolucion, cantidad, id_articulo, valor_unidad, fecha):
        self.id_devolucion = id_devolucion
        self.cantidad = cantidad
        self.id_articulo = id_articulo
        self.valor_unidad = valor_unidad
        self.fecha = fecha

    def ingresar(self):
        # Implementar la lógica para ingresar una devolución
        pass

    def modificar(self):
        # Implementar la lógica para modificar una devolución
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar una devolución
        pass

    def consultar(self):
        # Implementar la lógica para consultar una devolución
        pass
        class Venta:
    def __init__(self, id_venta, documento, id_articulo, fecha, cantidad, valor_unidad, id_cliente):
        self.id_venta = id_venta
        self.documento = documento
        self.id_articulo = id_articulo
        self.fecha = fecha
        self.cantidad = cantidad
        self.valor_unidad = valor_unidad
        self.id_cliente = id_cliente

    def ingresar(self):
        # Implementar la lógica para ingresar una venta
        pass

    def modificar(self):
        # Implementar la lógica para modificar una venta
        pass

    def consultar(self):
        # Implementar la lógica para consultar una venta
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar una venta
        pass

    def validar_articulo(self):
        # Implementar la lógica para validar el artículo de una venta
        pass
class Cliente:
    def __init__(self, id_cliente, nombre, documento, correo, telefono, direccion):
        self.id_cliente = id_cliente
        self.nombre = nombre
        self.documento = documento
        self.correo = correo
        self.telefono = telefono
        self.direccion = direccion

    def ingresar(self):
        # Implementar la lógica para ingresar un cliente
        pass

    def modificar(self):
        # Implementar la lógica para modificar un cliente
        pass

    def consultar(self):
        # Implementar la lógica para consultar un cliente
        pass

    def eliminar(self):
        # Implementar la lógica para eliminar un cliente
        pass
