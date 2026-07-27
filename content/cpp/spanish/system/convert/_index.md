---
title: Convert
second_title: Referencia de la API de Aspose.Slides para C++
description: "La estructura que contiene métodos que realizan la conversión de valores de un tipo a los valores de otro tipo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1561
url: /es/system/convert/
---
## Convertir struct

La estructura que contiene métodos que realizan la conversión de valores de un tipo a los valores de otro tipo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Convert
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NO IMPLEMENTADO. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Decodifica datos codificados en base-64 representados como un rango en la matriz de caracteres Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Decodifica datos codificados en base-64 representados como una cadena. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Devuelve un valor TypeCode que representa el tipo del valor boxed especificado. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NO IMPLEMENTADO. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NO IMPLEMENTADO Implementación falsa, verifica si el valor es nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Codifica en base-64 un rango de elementos en la matriz de bytes especificada y almacena los datos codificados como una matriz de caracteres Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica en base-64 un rango de elementos en la matriz de bytes especificada y almacena los datos codificados como una matriz de caracteres Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Codifica en base-64 elementos en la matriz de bytes especificada y devuelve los datos codificados como una cadena. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Codifica en base-64 un rango de elementos en la matriz de bytes especificada y devuelve los datos codificados como una cadena. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica en base-64 elementos en la matriz de bytes especificada y devuelve los datos codificados como una cadena. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica en base-64 un rango de elementos en la matriz de bytes especificada y devuelve los datos codificados como una cadena. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Devuelve el valor booleano especificado. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Convierte el número float especificado a un valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Convierte el número double especificado a un valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Convierte la cadena nula especificada al valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Convierte la c-string especificada al valor de tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Convierte la cadena especificada al valor de tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada al valor de tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor boxed especificado a un valor booleano equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Convierte el valor booleano especificado a un entero sin signo de 8 bits equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Devuelve el entero sin signo de 8 bits especificado. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Convierte el número float especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Convierte el número double especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Convierte el carácter unicode especificado a un entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Convierte la c-string especificada que contiene la representación en cadena de un número al valor entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación en cadena de un número en la base especificada al valor entero sin signo de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 8 bits equivalente usando la información de formato proporcionada. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 8 bits equivalente usando la información de formato y estilo numérico proporcionados. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor boxed especificado a un valor entero sin signo de 8 bits equivalente. |
| static char_t [ToChar](./tochar/)(**bool**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un carácter unicode equivalente. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un carácter unicode equivalente. |
| static char_t [ToChar](./tochar/)(**float**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Devuelve el carácter unicode especificado. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Convierte el primer y único carácter de la c-string especificada a un valor char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Convierte el primer y único carácter de la cadena especificada a un valor char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el primer y único carácter de la cadena especificada a un valor char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor boxed especificado a un carácter unicode equivalente. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Devuelve la fecha y hora especificadas. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Convierte la cadena especificada a una instancia de la clase [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada a una instancia de la clase [DateTime](../datetime/) usando la información de formato proporcionada. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado al valor [DateTime](../datetime/) equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Convierte el valor booleano especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Convierte el número float especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Convierte el número double especificado a un número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Devuelve el número decimal especificado. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Convierte la cadena nula especificada al valor [Decimal](../decimal/) equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Convierte la c-string especificada que contiene la representación de cadena de un número al valor [Decimal](../decimal/) equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor [Decimal](../decimal/) equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor [Decimal](../decimal/) equivalente usando la información de formato proporcionada. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor [Decimal](../decimal/) equivalente usando los estilos de número y la información de formato especificados. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado al valor [Decimal](../decimal/) equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Convierte el valor booleano especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Convierte el número de precisión simple especificado a un número de coma flotante de doble precisión equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Devuelve el número double especificado. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un número de coma flotante de doble precisión equivalente. |
| static **double** [ToDouble](./todouble/)(char_t) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Convierte la cadena nula especificada al valor de coma flotante de doble precisión equivalente. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Convierte la c-string especificada que contiene la representación de cadena de un número al valor de coma flotante de doble precisión equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor de coma flotante de doble precisión equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor de coma flotante de doble precisión equivalente usando la información de formato proporcionada. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor de coma flotante de doble precisión equivalente usando la información de formato y el estilo de número proporcionados. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a un valor de coma flotante de doble precisión. Si el tipo del valor encapsulado es [String](../string/), se utiliza el formato de cadena especificado durante la conversión. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Convierte el valor booleano especificado a un entero con signo de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero con signo de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero con signo de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Devuelve el entero con signo de 16 bits especificado. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Convierte el número float especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Convierte el número double especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Convierte el carácter unicode especificado a un entero con signo de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | La conversión no es compatible. Siempre lanza InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Convierte la c-string especificada que contiene la representación de cadena de un número al valor entero de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor entero de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación de cadena de un número en la base especificada al valor entero de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor entero de 16 bits equivalente usando la información de formato proporcionada. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación de cadena de un número al valor entero de 16 bits equivalente usando la información de formato y el estilo de número proporcionados. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado al valor entero de 16 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Convierte el valor booleano especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Devuelve el entero con signo de 32 bits especificado. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**float**) | Convierte el número float especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**double**) | Convierte el número double especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero con signo de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Convierte el carácter unicode especificado a un entero con signo de 32 bits equivalente. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const char_t *) | Convierte la cadena C especificada que contiene la representación textual de un número al valor entero de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 32 bits equivalente usando la información de formato proporcionada. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 32 bits equivalente usando la información de formato y el estilo numérico proporcionados. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a un valor entero de 32 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Convierte el valor booleano especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero con signo de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Devuelve el entero con signo de 64 bits especificado. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Convierte el número float especificado a un entero con signo de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Convierte el número double especificado a un entero con signo de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero con signo de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Convierte el carácter unicode especificado a un entero con signo de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Convierte la cadena C especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente usando la información de formato proporcionada. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 64 bits equivalente usando la información de formato y el estilo numérico proporcionados. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a un valor entero de 64 bits equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Convierte el valor booleano especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero con signo de 8 bits equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Devuelve el entero con signo de 8 bits especificado. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Convierte el número float especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Convierte el número double especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Convierte el carácter unicode especificado a un entero con signo de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Convierte la cadena C especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 8 bits equivalente usando la información de formato proporcionada. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero de 8 bits equivalente usando la información de formato y el estilo numérico proporcionados. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a un valor entero de 8 bits equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Convierte el valor booleano especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un número de punto flotante de precisión simple equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Devuelve el número float especificado. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Convierte el número de doble precisión especificado a un número de punto flotante de precisión simple equivalente. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un número de punto flotante de precisión simple equivalente. |
| static **float** [ToSingle](./tosingle/)(char_t) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Convierte la cadena nula especificada al valor equivalente de punto flotante de precisión simple. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Convierte la cadena C especificada que contiene la representación en forma de cadena de un número al valor equivalente de punto flotante de precisión simple. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor equivalente de punto flotante de precisión simple. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor equivalente de punto flotante de precisión simple usando la información de formato proporcionada. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor equivalente de punto flotante de precisión simple usando la información de formato y el estilo numérico proporcionados. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor en caja especificado a un valor de punto flotante de precisión simple. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a cadena usando la información de formato específica de la cultura. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena utilizando el formato de cadena especificado y la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Convierte el valor especificado a cadena. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Convierte el valor especificado a cadena utilizando el formato de cadena especificado. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Convierte el arreglo de caracteres Unicode especificado a cadena. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el arreglo de caracteres Unicode especificado a cadena utilizando la información de formato específica de cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Devuelve el valor especificado; no se realiza ninguna conversión. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Convierte el valor especificado a su representación en cadena. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Convierte el valor entero especificado a su representación en cadena en la base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Convierte el valor entero especificado a su representación en cadena en la base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Convierte el valor entero especificado a su representación en cadena en la base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Convierte el valor entero especificado a su representación en cadena en la base especificada. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a su representación en cadena. Si el tipo del valor encapsulado es [String](../string/), se utiliza el formato de cadena especificado durante la conversión. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Convierte el valor booleano especificado a un entero sin signo de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero sin signo de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Devuelve el entero sin signo de 16 bits especificado. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Convierte el número float especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Convierte el número double especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero sin signo de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Convierte el carácter Unicode especificado a un entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Conversión no soportada. Siempre lanza InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Convierte la cadena C especificada que contiene la representación en cadena de un número al valor entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación en cadena de un número en la base especificada al valor entero sin signo de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 16 bits equivalente utilizando la información de formato proporcionada. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor entero sin signo de 16 bits equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor encapsulado especificado a un valor entero sin signo de 16 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Convierte el valor booleano especificado a un entero sin signo de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero sin signo de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero sin signo de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Devuelve el entero sin signo de 32 bits especificado. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Convierte el entero sin signo de 64 bits especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Convierte el número de tipo float especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Convierte el número de tipo double especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero sin signo de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Convierte el carácter Unicode especificado a un entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Convierte la cadena C especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero sin signo de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente usando la información de formato proporcionada. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 32 bits equivalente usando la información de formato y el estilo numérico proporcionados. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor empaquetado especificado al valor entero sin signo de 32 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Convierte el valor booleano especificado a un entero sin signo de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Convierte el entero sin signo de 8 bits especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Convierte el entero con signo de 8 bits especificado a un entero sin signo de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Convierte el entero sin signo de 16 bits especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Convierte el entero con signo de 16 bits especificado a un entero sin signo de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Convierte el entero sin signo de 32 bits especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Convierte el entero con signo de 32 bits especificado a un entero sin signo de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Devuelve el entero sin signo de 64 bits especificado. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Convierte el entero con signo de 64 bits especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Convierte el número de tipo float especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Convierte el número de tipo double especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Convierte el número decimal especificado a un entero sin signo de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Convierte el carácter Unicode especificado a un entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | La conversión no está soportada. Siempre lanza InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Convierte la cadena nula especificada al valor entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Convierte la cadena C especificada que contiene la representación textual de un número al valor entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Convierte la cadena especificada que contiene la representación textual de un número en la base especificada al valor entero sin signo de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 64 bits equivalente usando la información de formato proporcionada. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al valor entero sin signo de 64 bits equivalente usando la información de formato y el estilo numérico proporcionados. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte el valor empaquetado especificado al valor entero sin signo de 64 bits equivalente. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)