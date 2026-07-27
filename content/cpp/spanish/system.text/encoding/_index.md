---
title: Encoding
second_title: Referencia de la API de Aspose.Slides para C++
description: Servicios de codificación.
type: docs
weight: 222
url: /es/system.text/encoding/
---
## Clase Encoding

[Encoding](./) servicios.

```cpp
class Encoding : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Clona el objeto de codificación. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Convierte bytes entre dos codificaciones. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Convierte bytes entre dos codificaciones. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara codificaciones. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Obtiene la codificación ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Obtiene el objeto de codificación Unicode big-endian estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Obtiene el objeto de codificación UTF-32 big-endian estándar. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Obtiene el nombre de codificación compatible con el cuerpo del agente de correo. |
| virtual int [get_CodePage](./get_codepage/)() | Obtiene la ID de página de códigos [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Obtiene la reserva del decodificador. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Obtiene la codificación predeterminada. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Obtiene la reserva del codificador. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Obtiene el nombre legible de la codificación. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Obtiene el nombre de codificación compatible con el encabezado del agente de correo. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Comprueba si la codificación puede usarse en el navegador para mostrar contenido. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Comprueba si la codificación puede usarse en el navegador para guardar contenido. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Comprueba si la codificación puede usarse en el cliente de correo para mostrar contenido. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Comprueba si la codificación puede usarse en el cliente de correo para guardar contenido. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Comprueba si la codificación es solo lectura. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Comprueba si la codificación es de un solo byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Obtiene la codificación Latin1. USO INTERNO. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Obtiene el objeto de codificación Unicode estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Obtiene el objeto de codificación UTF-7 estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Obtiene el objeto de codificación UTF-8 estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Solo interno, para ser usado por las bibliotecas de clases: sin marca y sin validación de entrada. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Obtiene el nombre de codificación compatible con IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Obtiene la ID de página de códigos [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Obtiene el número de caracteres necesarios para codificar una cadena. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencia asociada al objeto. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Obtiene un decodificador que reenvía solicitudes a este objeto. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Obtiene un codificador que reenvía solicitudes a este objeto. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Obtiene la codificación por nombre. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Obtiene la codificación por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtiene la codificación por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtiene la codificación por nombre. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Obtiene la lista de codificaciones conocidas. |
| int [GetHashCode](./gethashcode/)() const override | Calcula el hash de la codificación. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Obtiene la cantidad máxima de bytes necesarios para codificar un número especificado de caracteres. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Obtiene la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Devuelve una secuencia de bytes que denota la codificación (p. ej., BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodifica un búfer de bytes en una cadena. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodifica un búfer de bytes en una cadena. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodifica un búfer de bytes en una cadena. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodifica un búfer de bytes en una cadena. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodifica un búfer de bytes en una cadena. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodifica un búfer de bytes en una cadena. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción lock() de C# bloqueando. Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la copia en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la copia en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Establece la reserva del decodificador. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Establece la reserva del codificador. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla a un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción lock() de C# desbloqueando. Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Valor predeterminado de la página de códigos. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)