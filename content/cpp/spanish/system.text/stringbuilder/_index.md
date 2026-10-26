---
title: StringBuilder
second_title: Aspose.Slides para C++ Referencia de API
description: "Buffer para acumular la cadena parte a parte. Este tipo puede ser asignado ya sea en la pila como tipo valor o en el montón usando la función System::MakeObject(). Una vez el objeto está asignado, nunca mezcle estos dos casos de uso: tener punteros SmartPtr sobre objetos asignados en la pila está estrictamente prohibido."
type: docs
weight: 326
url: /es/system.text/stringbuilder/
---
## StringBuilder clase

[Buffer](../../system/buffer/) para acumular la cadena parte a parte. Este tipo puede ser asignado ya sea en la pila como tipo valor o en el montón usando la función [System::MakeObject()](../../system/makeobject/). Una vez el objeto está asignado, nunca mezcle estos dos casos de uso: tener punteros [SmartPtr](../../system/smartptr/) sobre objetos asignados en la pila está estrictamente prohibido.

```cpp
class StringBuilder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Agrega un carácter al constructor. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Agrega caracteres al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Agrega una matriz de caracteres al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Agrega una porción de la matriz de caracteres al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Agrega una cadena al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Agrega una porción de cadena al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Agrega la representación en cadena del objeto al constructor. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Agrega el contenido del constructor al constructor. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Agrega un valor de tipo **float** al constructor. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Agrega un valor de tipo **double** al constructor. |
| [StringBuilder](./) * [Append](./append/)(int) | Agrega un valor entero al constructor. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Agrega un valor aritmético al constructor. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Agrega la representación en cadena del valor enum al constructor. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Agrega una cadena formateada al constructor. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Agrega una cadena formateada al constructor. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Agrega un carácter de nueva línea al constructor. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Agrega una cadena seguida de un carácter de nueva línea al constructor. |
| [StringBuilder](./) * [Clear](./clear/)() | Elimina todos los caracteres del constructor. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Copia los datos del constructor a posiciones de matriz existentes. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Garantiza que la capacidad de esta instancia de [System.Text.StringBuilder](./) sea al menos el valor especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| int [get_Capacity](./get_capacity/)() const | Obtiene la capacidad actual del constructor de cadenas. |
| int [get_Length](./get_length/)() const | Obtiene la longitud de la cadena actualmente en el constructor. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Obtiene el carácter en la posición especificada. |
| void [idx_set](./idx_set/)(int, char_t) | Establece el carácter en la posición especificada. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Inserta una cadena en la posición fija del constructor. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Inserta una cadena repetida en la posición fija del constructor. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Inserta un carácter en la posición fija del constructor. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Inserta caracteres en la posición fija del constructor. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Inserta un valor en la posición fija del constructor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción copia de subclases. |
| char_t [operator[]](./operator[]/)(int) const | Obtiene el carácter en la posición especificada. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Elimina un fragmento del constructor. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Reemplaza una subcadena a través del constructor. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Reemplaza una subcadena dentro del rango del constructor. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Reemplaza un carácter a través del constructor. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Reemplaza un carácter dentro del rango del constructor. |
| void [set_Capacity](./set_capacity/)(int) | Establece la capacidad actual del constructor de cadenas. |
| void [set_Length](./set_length/)(int) | Trunca o amplía el constructor de cadenas a la longitud especificada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Constructor. |
|  [StringBuilder](./stringbuilder/)(int) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Constructor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Obtiene la cadena actualmente contenida en el constructor. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Obtiene la subcadena actualmente contenida en el constructor. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
|  [~StringBuilder](./~stringbuilder/)() | Destructor. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Text](../)
* Biblioteca [Aspose.Slides](../../)