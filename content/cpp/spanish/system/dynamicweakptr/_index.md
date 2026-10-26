---
title: DynamicWeakPtr
second_title: Referencia de API de Aspose.Slides para C++
description: Clase de puntero inteligente que rastrea los modos de puntero de los argumentos de plantilla del objeto almacenado y los actualiza después de cada asignación. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.
type: docs
weight: 781
url: /es/system/dynamicweakptr/
---
## Clase DynamicWeakPtr

Clase de puntero inteligente que rastrea los modos de puntero de los argumentos de plantilla del objeto almacenado y los actualiza después de cada asignación. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe ser asignado en la pila y pasado a funciones ya sea por valor o por referencia constante.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Pointee | tipo. |
| trunkMode | Modo del propio puntero inteligente, compartido o débil. |
| weakLeafs | Índices de los argumentos de plantilla del tipo almacenado que deben establecerse en modo puntero débil. |

## Métodos

| Método | Descripción |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accesor para el método [begin()](../smartptr/begin/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accesor para el método [begin()](../smartptr/begin/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero a su propio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accesor para el método [cbegin()](../smartptr/cbegin/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accesor para el método [cend()](../smartptr/cend/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast en el objeto apuntado. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast en el objeto apuntado. |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Crea un puntero inteligente nulo. |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Crea un puntero inteligente que apunta al objeto dado. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Construye una copia del puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Construye una copia del puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Construye una copia del puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Construye mediante movimiento el puntero inteligente. |
| auto [end](../smartptr/end/)() | Accesor para el método [end()](../smartptr/end/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accesor para el método [end()](../smartptr/end/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtiene el objeto apuntado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtiene el modo del puntero. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtiene el objeto apuntado, pero afirma que el puntero está en modo compartido. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtiene el número de punteros compartidos existentes al objeto referenciado, incluido el actual. Afirma que el puntero actual está en modo compartido. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Invoca [GetHashCode()](../smartptr/gethashcode/) en el objeto apuntado. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si lo hay) o lanza una excepción. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtiene el objeto referenciado. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica 'is' de C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto del propio (creado por un constructor de aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Comprueba si el puntero está en modo compartido. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit [operator bool](../smartptr/operator_bool/)() const | Comprueba si el puntero no es nulo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Comprueba si el puntero es nulo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtiene una referencia al objeto apuntado. Afirma que el puntero no es nulo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permite acceder a los miembros del objeto referenciado. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Asigna mediante movimiento el puntero inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Asigna mediante copia el puntero inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Asigna mediante copia el puntero inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Asigna el puntero inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Establece el puntero inteligente a nulo. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Comprueba si el puntero inteligente es nulo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Elimina el aliasing (creado por un constructor de aliasing) del puntero, asegurándose de que gestiona (si es compartido) o rastrea (si es débil) el mismo objeto al que apunta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Establece el objeto apuntado. |
| void [reset](../smartptr/reset/)() | Hace que el puntero apunte a nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Establece el modo del puntero. Puede alterar los contadores de referencia del objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Invoca el método SetTemplateWeakPtr() en el objeto apuntado (si lo hay). |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](../smartptr/) del modo requerido. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](../smartptr/) de puntero nulo del modo requerido. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](../smartptr/) que apunta al objeto especificado, o convierte un puntero sin procesar a [SmartPtr](../smartptr/). |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia un objeto [SmartPtr](../smartptr/). Ambos punteros apuntan al mismo objeto después. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia un objeto [SmartPtr](../smartptr/). Ambos punteros apuntan al mismo objeto después. Realiza conversión de tipo si está permitido. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construye por movimiento un objeto [SmartPtr](../smartptr/). Efectivamente, intercambia dos punteros si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convierte el tipo del arreglo referenciado creando un nuevo arreglo de tipo diferente. Útil si en C# hay un casting de tipo de arreglo que no está soportado en C++. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializa un arreglo vacío. Utilizado para traducir ciertos constructos de código C#. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construye un [SmartPtr](../smartptr/) que comparte la información de propiedad con el valor inicial de ptr, pero mantiene un puntero p no relacionado y no gestionado. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast en el objeto apuntado. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Convierte cualquier tipo de puntero a puntero a [Object](../object/). No requiere que el tipo Pointee_ esté completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Atajo para obtener el objeto [System::TypeInfo](../typeinfo/) para el tipo Pointee_. |
| [~SmartPtr](../smartptr/~smartptr/)() | Destruye el objeto [SmartPtr](../smartptr/). Si es necesario, decrementa el contador de referencias del objeto apuntado y elimina el objeto. |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [SmartPtr_](./smartptr_/) | alias de clase base [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias del tipo propio. |
| [Pointee_](./pointee_/) | Tipo apuntado. |

## Véase también

* Clase [SmartPtr](../smartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)