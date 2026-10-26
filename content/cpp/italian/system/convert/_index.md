---
title: Convert
second_title: Riferimento API di Aspose.Slides per C++
description: "La struttura che contiene i metodi che eseguono la conversione di valori da un tipo ai valori di un altro tipo. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 1561
url: /it/system/convert/
---
## Struttura di conversione

La struttura che contiene metodi per eseguire la conversione dei valori di un tipo in valori di un altro tipo. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class Convert
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NON IMPLEMENTATO. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Decodifica dati codificati in base-64 rappresentati come un intervallo nell'array di caratteri Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Decodifica dati codificati in base-64 rappresentati come una stringa. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Restituisce un valore TypeCode che rappresenta il tipo del valore boxed specificato. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NON IMPLEMENTATO. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NON IMPLEMENTATO Implementazione fittizia, verifica se il valore è nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Codifica in base-64 un intervallo di elementi nell'array di byte specificato e memorizza i dati codificati come un array di caratteri Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica in base-64 un intervallo di elementi nell'array di byte specificato e memorizza i dati codificati come un array di caratteri Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Codifica in base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come una stringa. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Codifica in base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come una stringa. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica in base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come una stringa. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica in base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come una stringa. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Restituisce il valore booleano specificato. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Converte il numero float specificato in un valore booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Converte il numero double specificato in un valore booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un valore booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Conversione non supportata. Genera sempre InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Conversione non supportata. Genera sempre InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Converte la c-string specificata al valore di tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Converte la stringa specificata al valore di tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata al valore di tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore booleano equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Converte il valore booleano specificato in un intero senza segno a 8 bit equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Restituisce l'intero senza segno a 8 bit specificato. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Converte il numero float specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Converte il numero double specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Converte il carattere unicode specificato in un intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Conversione non supportata. Genera sempre InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nella base specificata nel valore intero senza segno a 8 bit equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 8 bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 8 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero senza segno a 8 bit equivalente. |
| static char_t [ToChar](./tochar/)(**bool**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un carattere unicode equivalente. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un carattere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**float**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Conversione non supportata. Genera sempre InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Restituisce il carattere unicode specificato. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Conversione non supportata. Genera sempre InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Converte il primo e unico carattere della c-string specificata in un valore char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Converte il primo e unico carattere della stringa specificata in un valore char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il primo e unico carattere della stringa specificata in un valore char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un carattere unicode equivalente. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Conversione non supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Restituisce la data e l'ora specificate. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Converte la stringa specificata in un'istanza della classe [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata in un'istanza della classe [DateTime](../datetime/) utilizzando le informazioni di formattazione fornite. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore equivalente [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Converte il valore booleano specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Converte il numero float specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Converte il numero double specificato in un numero decimale equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Restituisce il numero decimale specificato. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore equivalente [Decimal](../decimal/) utilizzando le informazioni di formattazione fornite. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore equivalente [Decimal](../decimal/) utilizzando gli stili numerici e le informazioni di formattazione specificati. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore equivalente [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Converte il valore booleano specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Converte il numero a precisione singola specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Restituisce il numero double specificato. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un numero a virgola mobile a doppia precisione equivalente. |
| static **double** [ToDouble](./todouble/)(char_t) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore a virgola mobile a doppia precisione equivalente. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore a virgola mobile a doppia precisione. Se il tipo del valore boxed è [String](../string/), viene usato il formato stringa specificato durante la conversione. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Converte il valore booleano specificato in un intero con segno a 16 bit equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un intero con segno a 16 bit equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un intero con segno a 16 bit equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Restituisce l'intero con segno a 16 bit specificato. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Converte il numero float specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Converte il numero double specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Converte il carattere Unicode specificato in un intero con segno a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 16 bit equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 16 bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 16 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero a 16 bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Converte il valore booleano specificato in un intero con segno a 32 bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un intero con segno a 32 bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Converte l'intero con segno a 8-bit specificato in un intero con segno a 32-bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Converte l'intero senza segno a 16-bit specificato in un intero con segno a 32-bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Converte l'intero con segno a 16-bit specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Converte l'intero senza segno a 32-bit specificato in un intero con segno a 32-bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Restituisce l'intero con segno a 32-bit specificato. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Converte l'intero senza segno a 64-bit specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(**int64_t**) | Converte l'intero con segno a 64-bit specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(**float**) | Converte il valore float specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(**double**) | Converte il valore double specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero con segno a 32-bit equivalente. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Converte il carattere Unicode specificato in un intero con segno a 32-bit equivalente. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Conversione non supportata. Lancia sempre InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(const char_t *) | Converte la stringa C contenente la rappresentazione testuale di un numero nel valore intero a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Converte la stringa contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 32-bit equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 32-bit equivalente utilizzando le informazioni di formattazione fornite. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 32-bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero a 32-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Converte il valore booleano specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Converte l'intero senza segno a 8-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Converte l'intero con segno a 8-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Converte l'intero senza segno a 16-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Converte l'intero con segno a 16-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Converte l'intero senza segno a 32-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Converte l'intero con segno a 32-bit specificato in un intero con segno a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Converte l'intero senza segno a 64-bit specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Restituisce l'intero con segno a 64-bit specificato. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Converte il valore float specificato in un intero con segno a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Converte il valore double specificato in un intero con segno a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero con segno a 64-bit equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Converte il carattere Unicode specificato in un intero con segno a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Conversione non supportata. Lancia sempre InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Converte la stringa C contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Converte la stringa contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 64-bit equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero a 64-bit equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Converte il valore booleano specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Converte l'intero senza segno a 8-bit specificato in un intero con segno a 8-bit equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Restituisce l'intero con segno a 8-bit specificato. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Converte l'intero senza segno a 16-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Converte l'intero con segno a 16-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Converte l'intero senza segno a 32-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Converte l'intero con segno a 32-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Converte l'intero senza segno a 64-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Converte l'intero con segno a 64-bit specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Converte il valore float specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Converte il valore double specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Converte il carattere Unicode specificato in un intero con segno a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Conversione non supportata. Lancia sempre InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Converte la stringa C contenente la rappresentazione testuale di un numero nel valore intero a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Converte la stringa contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 8-bit equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero senza segno a 8-bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 8-bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero a 8-bit equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Converte il valore booleano specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Converte l'intero senza segno a 8-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Converte l'intero con segno a 8-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Converte l'intero senza segno a 16-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Converte l'intero con segno a 16-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Converte l'intero senza segno a 32-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Converte l'intero con segno a 32-bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un numero a virgola mobile a precisione singola equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Restituisce il numero float specificato. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Converte il numero a doppia precisione specificato in un numero a virgola mobile a precisione singola equivalente. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un numero a virgola mobile a precisione singola equivalente. |
| static **float** [ToSingle](./tosingle/)(char_t) | Conversione non supportata. Lancia sempre InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Conversione non supportata. Lancia sempre InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore a virgola mobile a precisione singola equivalente. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore floating-point a precisione singola. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato in stringa utilizzando le informazioni di formattazione specifiche della cultura. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Converte il valore specificato in stringa. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Converte il valore specificato in stringa usando il formato stringa specificato. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Converte l'array specificato di caratteri Unicode in stringa. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte l'array specificato di caratteri Unicode in stringa utilizzando le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Restituisce il valore specificato; nessuna conversione viene eseguita. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Converte il valore specificato nella sua rappresentazione stringa. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Converte il valore intero specificato nella sua rappresentazione stringa nella base specificata. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Converte il valore intero specificato nella sua rappresentazione stringa nella base specificata. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Converte il valore intero specificato nella sua rappresentazione stringa nella base specificata. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Converte il valore intero specificato nella sua rappresentazione stringa nella base specificata. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato nella sua rappresentazione stringa. Se il tipo del valore boxed è [String](../string/), viene usato il formato stringa specificato durante la conversione. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Converte il valore booleano specificato in un intero senza segno a 16 bit equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Converte l'intero a 8 bit con segno specificato in un intero senza segno a 16 bit equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Restituisce l'intero senza segno a 16 bit specificato. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Converte l'intero a 16 bit con segno specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Converte l'intero a 32 bit con segno specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Converte l'intero a 64 bit con segno specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Converte il numero float specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Converte il numero double specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero senza segno a 16 bit equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Converte il carattere Unicode specificato in un intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | La conversione non è supportata. Genera sempre InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Converte la c-stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nella base specificata nel valore intero senza segno a 16 bit equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione e lo stile numerico forniti. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero senza segno a 16 bit equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Converte il valore booleano specificato in un intero senza segno a 32 bit equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Converte l'intero a 8 bit con segno specificato in un intero senza segno a 32 bit equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Converte l'intero a 16 bit con segno specificato in un intero senza segno a 32 bit equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Restituisce l'intero senza segno a 32 bit specificato. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Converte l'intero senza segno a 64 bit specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Converte il numero float specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Converte il numero double specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero senza segno a 32 bit equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Converte il carattere unicode specificato in un intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | La conversione non è supportata. Lancia sempre InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero senza segno a 32 bit equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxed specificato in un valore intero senza segno a 32 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Converte il valore booleano specificato in un intero senza segno a 64 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Converte l'intero senza segno a 8 bit specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Converte l'intero con segno a 8 bit specificato in un intero senza segno a 64 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Converte l'intero senza segno a 16 bit specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Converte l'intero con segno a 16 bit specificato in un intero senza segno a 64 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Converte l'intero senza segno a 32 bit specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Converte l'intero con segno a 32 bit specificato in un intero senza segno a 64 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Restituisce l'intero senza segno a 64 bit specificato. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Converte l'intero con segno a 64 bit specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Converte il numero float specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Converte il numero double specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Converte il numero decimale specificato in un intero senza segno a 64 bit equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Converte il carattere unicode specificato in un intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | La conversione non è supportata. Lancia sempre InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Converte la stringa nulla specificata nel valore intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero senza segno a 64 bit equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente utilizzando le informazioni di formattazione fornite. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte il valore boxato specificato in un valore intero senza segno a 64 bit equivalente. |
## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)