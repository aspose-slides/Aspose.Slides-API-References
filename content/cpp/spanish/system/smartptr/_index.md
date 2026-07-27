---
title: SmartPtr
second_title: Aspose.Slides para la referencia de API de C++
description: "Clase puntero para envolver tipos asignados en el heap. Úsela para gestionar la memoria de clases que heredan de Object. Este tipo de puntero sigue la semántica de punteros intrusivos. El contador de referencias se almacena ya sea en Object mismo o en una estructura de contador que está estrechamente vinculada a la instancia de Object. En cualquier caso, todas las instancias de SmartPtr forman un único grupo de propiedad independientemente de cómo fueron creadas, lo que difiere del comportamiento de la clase std::shared_ptr. Convertir un puntero crudo a SmartPtr es seguro siempre que existan otras instancias de SmartPtr que mantengan referencias compartidas al mismo objeto. Una instancia de la clase SmartPtr puede estar en uno de dos estados: puntero compartido y puntero débil. Para mantener el objeto vivo, debe haber un recuento positivo de referencias compartidas hacia él. Tanto los punteros débiles como los compartidos pueden usarse para acceder al objeto apuntado (para llamar a métodos, leer o escribir campos, etc.), pero los punteros débiles no participan en el conteo de referencias del puntero compartido. Object se elimina cuando el último puntero 'shared' SmartPtr a él es destruido. Por lo tanto, asegúrese de que esto no ocurra cuando no existan otros punteros compartidos SmartPtr al objeto, por ejemplo durante la construcción o destrucción del objeto. Use los objetos centinela System::Object::ThisProtector (en código C++) o los atributos CppCTORSelfReference o CppSelfReference (en código C# que se traduce) para corregir este problema. De forma similar, asegúrese de romper referencias en bucle usando la clase puntero System::WeakPtr o el modo puntero System::SmartPtrMode::Weak (en código C++) o el atributo CppWeakPtr (en código C# que se traduce). Si dos o más objetos se referencian entre sí usando punteros 'shared', nunca se eliminarán. Si el tipo de puntero (débil o compartido) debe cambiarse en tiempo de ejecución, use el método System::SmartPtr<T>::set_Mode() o la clase System::DynamicWeakPtr. La clase SmartPtr no contiene métodos virtuales. Sólo debe heredarla si está creando su propia estrategia de gestión de memoria. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante."
type: docs
weight: 1236
url: /es/system/smartptr/
---
## SmartPtr clase

Clase puntero para envolver tipos asignados en el montón. Úsela para gestionar la memoria de clases que heredan de [Object](../object/). Este tipo de puntero sigue la semántica de punteros intrusivos. El contador de referencias se almacena ya sea en [Object](../object/) mismo o en una estructura de contador que está fuertemente vinculada a la instancia de [Object](../object/). En cualquier caso, todas las instancias de [SmartPtr](./) forman un único grupo de propiedad sin importar cómo fueron creadas, lo cual difiere del comportamiento de la clase std::shared_ptr. Convertir un puntero crudo a [SmartPtr](./) es seguro siempre que existan otras instancias de [SmartPtr](./) que mantengan referencias compartidas al mismo objeto. Una instancia de la clase [SmartPtr](./) puede estar en uno de dos estados: puntero compartido y puntero débil. Para mantener el objeto vivo, se debe tener un recuento positivo de referencias compartidas hacia él. Tanto los punteros débiles como los compartidos pueden usarse para acceder al objeto apuntado (para llamar a métodos, leer o escribir campos, etc.), pero los punteros débiles no participan en el conteo de referencias del puntero compartido. [Object](../object/) se elimina cuando el último puntero 'shared' [SmartPtr](./) a él es destruido. Por lo tanto, asegúrese de que esto no ocurra cuando no existan otros punteros compartidos [SmartPtr](./) al objeto, por ejemplo, durante la construcción o destrucción del objeto. Use los objetos centinela System::Object::ThisProtector (en código C++) o los atributos CppCTORSelfReference o CppSelfReference (en código C# que se traduce) para corregir este problema. De manera similar, asegúrese de romper referencias circulares usando la clase puntero [System::WeakPtr](../weakptr/) o el modo puntero [System::SmartPtrMode::Weak](../smartptrmode/) (en código C++) o el atributo CppWeakPtr (en código C# que se traduce). Si dos o más objetos se referencian entre sí usando punteros 'shared', nunca se eliminarán. Si el tipo de puntero (débil o compartido) debe cambiarse en tiempo de ejecución, use el método [System::SmartPtr<T>::set_Mode()](./set_mode/) o la clase [System::DynamicWeakPtr](../dynamicweakptr/). La clase [SmartPtr](./) no contiene métodos virtuales. Solo debe heredarla si está creando su propia estrategia de gestión de memoria. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
template<class T>class SmartPtr
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del objeto apuntado. Debe ser [System::Object](../object/) o una subclase de él. |

## Métodos

| Method | Description |
| --- | --- |
| auto [begin](./begin/)() | Accesor del método [begin()](./begin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [begin()](./begin/). |
| auto [begin](./begin/)() const | Accesor del método [begin()](./begin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convierte el puntero a su propio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Accesor del método [cbegin()](./cbegin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Accesor del método [cend()](./cend/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast sobre el objeto apuntado. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast sobre el objeto apuntado. |
| auto [end](./end/)() | Accesor del método [end()](./end/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [end()](./end/). |
| auto [end](./end/)() const | Accesor del método [end()](./end/) de una colección subyacente. Sólo compila si SmartPtr_ es un tipo de especialización con el método [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Obtiene el objeto apuntado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Obtiene el modo del puntero. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Obtiene el objeto apuntado, pero afirma que el puntero está en modo compartido. |
| int [get_shared_count](./get_shared_count/)() const | Obtiene el número de punteros compartidos existentes al objeto referenciado, incluido el actual. Afirma que el puntero actual está en modo compartido. |
| int [GetHashCode](./gethashcode/)() const | Llama a [GetHashCode()](./gethashcode/) sobre el objeto apuntado. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si lo hay) o lanza una excepción. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Equivalente a [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Obtiene el objeto referenciado. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Equivalente a [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica 'is' de C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto al poseído (creado por un constructor de alias). |
| **bool** [IsShared](./isshared/)() const | Comprueba si el puntero está en modo compartido. |
| **bool** [IsWeak](./isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit  [operator bool](./operator_bool/)() const | Comprueba si el puntero no es nulo. |
| **bool** [operator!](./operator_not/)() const | Comprueba si el puntero es nulo. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Obtiene una referencia al objeto apuntado. Afirma que el puntero no es nulo. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Permite acceder a los miembros del objeto referenciado. |
| **bool** [operator<](./operator_less/)(Y *) const | Proporciona semántica de comparación menor para la clase [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Proporciona semántica de comparación menor para la clase [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Assigna por movimiento el objeto [SmartPtr](./). x queda inutilizable. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Assigna por copia el objeto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Assigna por copia el objeto [SmartPtr](./). Realiza las conversiones de tipo requeridas. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Asignar puntero crudo al objeto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Establece el valor del puntero a nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Comprueba si el puntero apunta a nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Elimina el aliasing (creado por un constructor de alias) del puntero, asegurándose de que gestione (si es compartido) o rastree (si es débil) el mismo objeto al que apunta. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Establece el objeto apuntado. |
| void [reset](./reset/)() | Hace que el puntero apunte a nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Establece el modo del puntero. Puede alterar los contadores de referencia del objeto referenciado. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Llama al método SetTemplateWeakPtr() sobre el objeto apuntado (si lo hay). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](./) del modo requerido. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](./) de puntero nulo del modo requerido. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](./) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia el objeto [SmartPtr](./). Ambos punteros apuntan al mismo objeto después. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia el objeto [SmartPtr](./). Ambos punteros apuntan al mismo objeto después. Realiza la conversión de tipo si está permitida. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construye por movimiento el objeto [SmartPtr](./). Efectivamente, intercambia dos punteros si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convierte el tipo de la matriz referenciada creando una nueva matriz de tipo diferente. Útil si en C# hay un casteo de matriz que no está soportado en C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Inicializa una matriz vacía. Usado para traducir algunas construcciones de código C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construye un [SmartPtr](./) que comparte la información de propiedad con el valor inicial de ptr, pero mantiene un puntero p no relacionado y sin gestión. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast sobre el objeto apuntado. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Convierte cualquier tipo de puntero a un puntero a [Object](../object/). No requiere que el tipo Pointee_ esté completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Acceso rápido para obtener el objeto [System::TypeInfo](../typeinfo/) del tipo Pointee_. |
|  [~SmartPtr](./~smartptr/)() | Destruye el objeto [SmartPtr](./). Si es necesario, disminuye el contador de referencias del objeto apuntado y elimina el objeto. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | Tipo apuntado. |
| [SmartPtr_](./smartptr_/) | Tipo de smart pointer especializado. |
| [ArrayType](./arraytype/) | Igual que Pointee_, si es una especialización de [System::Array](../array/), y void en caso contrario. |
| [ValueType](./valuetype/) | Tipo de almacenamiento del array apuntado. Sólo tiene sentido si T es una especialización de [System::Array](../array/). |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)