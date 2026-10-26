---
title: StreamWriter
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un escritor que escribe caracteres en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 391
url: /es/system.io/streamwriter/
---
## Clase StreamWriter

Representa un escritor que escribe caracteres en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Close](./close/)() override | Cierra el flujo y libera los recursos adquiridos. |
| void [Dispose](./dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual void [Dispose](./dispose/)(**bool**) | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| void [Flush](./flush/)() override | Vacia el contenido del búfer al flujo subyacente y luego vacía el flujo subyacente. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Devuelve un valor que indica si [StreamWriter](./) vaciará los datos al flujo subyacente cada vez que se llame al método [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Devuelve un puntero compartido a un objeto que representa el flujo subyacente. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Devuelve la codificación actualmente usada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente usado. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente usado. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Devuelve una cadena terminadora de línea. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Devuelve una cadena terminadora de línea. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Devuelve un valor que especifica si [StreamWriter](./) debe vaciar los datos al flujo subyacente cada vez que se llame al método [StreamWriter::Write](./write/). |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Establece una cadena terminadora de línea. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el argumento de plantilla n-ésimo como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al flujo subyacente especificado usando codificación UTF-8 y un búfer de tamaño predeterminado de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al flujo subyacente especificado usando la codificación especificada y un búfer de tamaño predeterminado de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si el flujo subyacente debe cerrarse cuando se disponga del objeto [StreamWriter](./). |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al archivo especificado usando codificación UTF-8 y un búfer de tamaño predeterminado de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al archivo especificado usando la codificación especificada y un búfer de tamaño predeterminado de 1024 bytes. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres al archivo especificado usando la codificación especificada y el tamaño de búfer. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [Write](./write/)(char_t) override | Escribe el carácter especificado al flujo. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Escribe la cadena especificada al flujo. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Escribe la representación en cadena del objeto especificado al flujo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Escribe todos los caracteres del arreglo especificado al flujo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado al flujo. |
| void [Write](./write/)(const char_t *) override | Escribe la cadena C especificada al flujo. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Escribe la representación en cadena del objeto especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**bool**) | Escribe la representación en cadena del valor booleano especificado al flujo. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**double**) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado al flujo. |
| virtual void [Write](../textwriter/write/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**float**) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado al flujo. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado al flujo. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato dado al flujo. |
| void [WriteLine](./writeline/)() override | Escribe los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Escribe la cadena especificada seguida de los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Escribe la representación en cadena del objeto especificado seguida de los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Escribe todos los caracteres del arreglo especificado seguido de los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado seguido de los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const char_t *) override | Escribe la cadena C especificada seguida de los caracteres terminadores de línea al flujo. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Escribe la representación en cadena del objeto especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Escribe la representación en cadena del valor booleano especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Escribe el carácter especificado seguido de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Escribe la representación en cadena del valor entero de 64 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado seguida de los caracteres terminadores de línea al flujo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado seguida de los caracteres terminadores de línea al flujo. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato dado seguidos de los caracteres terminadores de línea al flujo. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
|  [~StreamWriter](./~streamwriter/)() | Destructor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |

## Ver también

* Clase [TextWriter](../textwriter/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)