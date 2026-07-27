---
title: TextWriter
second_title: Referencia de API de Aspose.Slides para C++
description: "Una clase base para clases que representan escritores que escriben secuencias de caracteres en diferentes destinos. Los objetos de esta clase sólo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 443
url: /es/system.io/textwriter/
---
## TextWriter class


Una clase base para clases que representan escritores que escriben secuencias de caracteres a diferentes destinos. Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class TextWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Cierra el flujo y libera los recursos adquiridos. |
| void [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| virtual void [Flush](./flush/)() | Vacía el contenido del búfer al flujo subyacente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Devuelve la codificación usada actualmente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) usado actualmente. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) usado actualmente. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Devuelve una cadena terminadora de línea. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Devuelve una cadena terminadora de línea. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# `lock()`. Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada realmente, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada realmente, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Establece una cadena terminadora de línea. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# `lock()`. Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escribe la representación en cadena del objeto especificado en el flujo. |
| virtual void [Write](./write/)(**bool**) | Escribe la representación en cadena del valor booleano especificado en el flujo. |
| virtual void [Write](./write/)(char_t) | Escribe el carácter especificado en el flujo. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado en el flujo. |
| virtual void [Write](./write/)(**double**) | Escribe la representación en cadena del valor de coma flotante de doble precisión especificado en el flujo. |
| virtual void [Write](./write/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado en el flujo. |
| virtual void [Write](./write/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado en el flujo. |
| virtual void [Write](./write/)(**float**) | Escribe la representación en cadena del valor de coma flotante de precisión simple especificado en el flujo. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Escribe la cadena especificada en el flujo. |
| virtual void [Write](./write/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado en el flujo. |
| virtual void [Write](./write/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado en el flujo. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escribe todos los caracteres del arreglo especificado en el flujo. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado en el flujo. |
| virtual void [Write](./write/)(const char_t *) | Escribe la cadena C especificada en el flujo. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado en el flujo. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato indicado en el flujo. |
| virtual void [WriteLine](./writeline/)() | Escribe los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escribe la representación en cadena del objeto especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**bool**) | Escribe la representación en cadena del valor booleano especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(char_t) | Escribe el carácter especificado seguido de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**double**) | Escribe la representación en cadena del valor de coma flotante de doble precisión especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**float**) | Escribe la representación en cadena del valor de coma flotante de precisión simple especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Escribe la cadena especificada seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escribe todos los caracteres del arreglo especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Escribe la cadena C especificada seguida de los caracteres terminadores de línea en el flujo. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado seguida de los caracteres terminadores de línea en el flujo. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato indicado seguida de los caracteres terminadores de línea en el flujo. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
| virtual  [~TextWriter](./~textwriter/)() | Destructor. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a esta clase. |

## Ver también

* Clase [IDisposable](../../system/idisposable/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)