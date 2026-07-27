---
title: UnicodeEncoding
second_title: Referencia de la API de Aspose.Slides para C++
description: "Codificación Unicode. Los objetos de esta clase solo deben asignarse usando System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando operator new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 339
url: /es/system.text/unicodeencoding/
---
## Clase UnicodeEncoding

Codificación Unicode. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Métodos

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clona el objeto de codificación. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Convierte bytes entre dos codificaciones. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Convierte bytes entre dos codificaciones. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara codificaciones. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Obtiene la codificación ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Obtiene el objeto de codificación Unicode estándar de big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Obtiene el objeto de codificación UTF-32 estándar de big-endian. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Obtiene el nombre de codificación compatible con el cuerpo del agente de correo. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Obtiene el ID de página de códigos [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Obtiene el fallback del decodificador. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Obtiene la codificación predeterminada. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Obtiene el fallback del codificador. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Obtiene el nombre de codificación legible por humanos. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Obtiene el nombre de codificación compatible con la cabecera del agente de correo. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Comprueba si la codificación puede usarse en el navegador para mostrar contenido. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Comprueba si la codificación puede usarse en el navegador para guardar contenido. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Comprueba si la codificación puede usarse en el cliente de correo para mostrar contenido. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Comprueba si la codificación puede usarse en el cliente de correo para guardar contenido. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Comprueba si la codificación es de solo lectura. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Comprueba si la codificación es de un solo byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Obtiene la codificación Latin1. PARA USO INTERNO. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Obtiene el objeto de codificación Unicode estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Obtiene el objeto de codificación UTF-7 estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Obtiene el objeto de codificación UTF-8 estándar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Solo interno, para ser usado por las bibliotecas de clases: sin marca y sin validación de entrada. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Obtiene el nombre de codificación compatible con IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Obtiene el ID de página de códigos [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Obtiene un decodificador que reenvía solicitudes a este objeto. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Obtiene un codificador que reenvía solicitudes a este objeto. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Obtiene la codificación por nombre. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Obtiene la codificación por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtiene la codificación por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtiene la codificación por nombre. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Obtiene la lista de codificaciones conocidas. |
| int [GetHashCode](./gethashcode/)() const override | Calcula el hash de la codificación. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Obtiene el número máximo de bytes necesarios para codificar un número especificado de caracteres. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Obtiene el número máximo de caracteres necesarios para decodificar un número especificado de bytes. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Devuelve una secuencia de bytes que indica la codificación (p. ej., BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Decodifica un búfer de bytes a una cadena. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodifica un búfer de bytes a una cadena. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodifica un búfer de bytes a una cadena. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodifica un búfer de bytes a una cadena. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodifica un búfer de bytes a una cadena. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodifica un búfer de bytes a una cadena. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodifica un búfer de bytes a una cadena. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodifica un búfer de bytes a una cadena. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| **bool** [operator==](./operator_equal_equal/)(const [UnicodeEncoding](./)\&) const | Compara codificaciones por páginas de códigos y banderas. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Compara codificaciones usando páginas de códigos. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Establece el fallback del decodificador. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Establece el fallback del codificador. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
|  [UnicodeEncoding](./unicodeencoding/)() | Constructor. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**) | Constructor. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**, **bool**) | Constructor. |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Número de página de códigos big endian. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Valor predeterminado de página de códigos. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Número de página de códigos little endian. |

## Ver también

* Clase [ICUEncoding](../icuencoding/)
* Espacio de nombres [System::Text](../)
* Biblioteca [Aspose.Slides](../../)