---
title: StringWriter
second_title: Referencia de la API de Aspose.Slides para C++
description: "Implementa un TextWriter que escribe información en una cadena. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 417
url: /es/system.io/stringwriter/
---
## StringWriter clase

Implementa un [TextWriter](../textwriter/) que escribe información en una cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Cierra el flujo y libera los recursos adquiridos. |
| void [Dispose](../textwriter/dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual void [Flush](../textwriter/flush/)() | Vuelca el contenido del búfer al flujo subyacente. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Devuelve la codificación actualmente utilizada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente usado. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente usado. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Devuelve una cadena terminadora de línea. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Devuelve una cadena terminadora de línea. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Devuelve el StringBuilder actualmente usado. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras internas de datos. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Establece una cadena terminadora de línea. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construye una nueva instancia de [StringWriter](./) usando el StringBuilder especificado y [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Construye una nueva instancia de [StringWriter](./) usando el StringBuilder especificado y [IFormatProvider](../../system/iformatprovider/) de la cultura actual. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construye una nueva instancia de [StringWriter](./) usando el [IFormatProvider](../../system/iformatprovider/) especificado. |
|  [StringWriter](./stringwriter/)() | Construye una nueva instancia de [StringWriter](./) usando [IFormatProvider](../../system/iformatprovider/) de la cultura actual. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Devuelve la cadena subyacente. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Write](./write/)(char_t) override | Escribe el carácter especificado al flujo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Escribe el subrango especificado de caracteres del array de caracteres especificado al flujo. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Escribe la cadena especificada al flujo. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escribe la representación en cadena del objeto especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**bool**) | Escribe la representación en cadena del valor booleano especificado al flujo. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**double**) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado al flujo. |
| virtual void [Write](../textwriter/write/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**float**) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escribe todos los caracteres del array especificado al flujo. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Escribe la cadena C especificada al flujo. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado al flujo. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato especificado al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)() | Escribe los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escribe la representación en cadena del objeto especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Escribe la representación en cadena del valor booleano especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Escribe el carácter especificado seguido de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Escribe la cadena especificada seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escribe todos los caracteres del array especificado seguidos de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escribe el subrango especificado de caracteres UTF-16 del array de caracteres especificado seguido de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Escribe la cadena C especificada seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado seguida de los caracteres terminadores de línea al flujo. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato especificado seguidos de los caracteres terminadores de línea al flujo. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras internas de datos. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |
## Véase también

* Clase [TextWriter](../textwriter/)
* Espacio de nombres [System::IO](../)
* Library [Aspose.Slides](../../)