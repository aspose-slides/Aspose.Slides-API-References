---
title: Object
second_title: Referencia de API de Aspose.Slides para C++
description: Clase base que permite usar los métodos disponibles para la clase System.Object en C#. Todas las clases no triviales usadas con el entorno traducido deben heredarla.
type: docs
weight: 1132
url: /es/system/object/
---
## Object clase


Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## Métodos

| Method | Descripción |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](./gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](./lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](./memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](./object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](./object/)([Object](./) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia al construir subclases. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia al construir subclases. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](./referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](./referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](./sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Análogo al método C# [Object.ToString()](./tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementa la construcción C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](./~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ptr](./ptr/) | Alias para el tipo de puntero inteligente. |

## Observaciones

Además de los métodos disponibles en la clase C# [System.Object](./), también permite soporte para algunos conceptos específicos del entorno de código traducido. Esto incluye el recuento de referencias utilizado por las clases de punteros inteligentes ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) y otros servicios relacionados con la gestión de memoria, depuración, etc.

Cada [Object](./) tiene dos contadores de referencia: contador de referencia compartida y contador de referencia débil. El contador de referencia débil siempre se almacena en una estructura de datos separada en lugar de en [Object](./) mismo, lo que permite que los punteros débiles sobrevivan al objeto referenciado. El contador de referencia inteligente se almacena ya sea en el propio objeto o en la misma estructura separada, según el estado de la macro ENABLE_EXTERNAL_REFCOUNT. Por defecto, está habilitado en compilaciones de depuración y deshabilitado en compilaciones de lanzamiento. Si el contador del puntero inteligente se almacena en el propio objeto, la estructura de datos separada se crea solo si existen punteros débiles al objeto. De lo contrario, se crea junto con el propio objeto.

Todos los punteros inteligentes usan estos dos contadores de referencia y contribuyen al mismo y único grupo de propiedad.

Si la subclase [Object](./) se crea en la pila, no se pueden crear punteros inteligentes a ella; de lo contrario, hay un problema de eliminación de la pila.

Este tipo puede asignarse ya sea en la pila como tipo valor o en el heap usando la función [System::MakeObject()](../makeobject/). Una vez que el objeto está asignado, nunca mezcle estos dos casos de uso: tener punteros [SmartPtr](../smartptr/) a objetos asignados en la pila está estrictamente prohibido.

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)