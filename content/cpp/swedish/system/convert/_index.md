---
title: Convert
second_title: Aspose.Slides för C++ API-referens
description: "Strukturen som innehåller metoder som utför konvertering av värden av en typ till värden av en annan typ. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 1561
url: /sv/system/convert/
---
## Konvertera struktur

Strukturen som innehåller metoder för att konvertera värden av en typ till värden av en annan typ. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller som referens. Använd aldrig klassen [System::SmartPtr](../smartptr/) för att hantera objekt av denna typ.

```cpp
class Convert
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | INTE IMPLEMENTERAD. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Avkodar base-64-kodad data som representeras som ett intervall i arrayen av Unicode-tecken. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Avkodar base-64-kodad data som representeras som en sträng. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Returnerar ett TypeCode-värde som representerar typen av det angivna förpackade värdet. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | INTE IMPLEMENTERAD. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | INTE IMPLEMENTERAD Falsk implementation, kontrollerar om värdet är nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Base-64-kodar ett intervall av element i den angivna byte-arrayen och lagrar den kodade datan som en array av Unicode-tecken. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64-kodar ett intervall av element i den angivna byte-arrayen och lagrar den kodade datan som en array av Unicode-tecken. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Base-64-kodar element i den angivna byte-arrayen och returnerar den kodade datan som en sträng. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Base-64-kodar ett intervall av element i den angivna byte-arrayen och returnerar den kodade datan som en sträng. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64-kodar element i den angivna byte-arrayen och returnerar den kodade datan som en sträng. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64-kodar ett intervall av element i den angivna byte-arrayen och returnerar den kodade datan som en sträng. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Returnerar det angivna booleska värdet. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Konverterar det angivna 8-bits osignerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Konverterar det angivna 8-bits signerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Konverterar det angivna 16-bits osignerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Konverterar det angivna 16-bits signerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Konverterar det angivna 32-bits osignerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Konverterar det angivna 32-bits signerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Konverterar det angivna 64-bits osignerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Konverterar det angivna 64-bits signerade heltalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande booleskt värde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Konverterar det angivna double-värdet till ett motsvarande booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Konverterar den angivna C-strängen till ett booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Konverterar den angivna strängen till ett booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen till ett booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till ett motsvarande booleskt värde. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 8-bits osignerat heltal. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Returnerar det angivna 8-bits osignerade heltalet. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Konverterar det angivna 8-bits signerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Konverterar det angivna 16-bits osignerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Konverterar det angivna 16-bits signerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Konverterar det angivna 32-bits osignerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Konverterar det angivna 32-bits signerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Konverterar det angivna 64-bits osignerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Konverterar det angivna 64-bits signerade heltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Konverterar det angivna double-värdet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 8-bits osignerat heltal. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande osignerade 8-bits heltalsvärde. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Konverterar den angivna C-strängen som innehåller talets textrepresentation till motsvarande osignerade 8-bits heltalsvärde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande osignerade 8-bits heltalsvärde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets textrepresentation i den angivna basen till motsvarande osignerade 8-bits heltalsvärde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande osignerade 8-bits heltalsvärde med hjälp av den angivna formateringsinformationen. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande osignerade 8-bits heltalsvärde med hjälp av den angivna formateringsinformationen och talstilen. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande osignerade 8-bits heltalsvärde. |
| static char_t [ToChar](./tochar/)(**bool**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Konverterar det angivna 8-bits osignerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Konverterar det angivna 8-bits signerade heltalet till ett motsvarande Unicode-tecken. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Konverterar det angivna 16-bits osignerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Konverterar det angivna 16-bits signerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Konverterar det angivna 32-bits osignerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Konverterar det angivna 32-bits signerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Konverterar det angivna 64-bits osignerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Konverterar det angivna 64-bits signerade heltalet till ett motsvarande Unicode-tecken. |
| static char_t [ToChar](./tochar/)(**float**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Returnerar det angivna Unicode-tecknet. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Konverterar det första och enda tecknet i den angivna C-strängen till ett char_t-värde. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Konverterar det första och enda tecknet i den angivna strängen till ett char_t-värde. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det första och enda tecknet i den angivna strängen till ett char_t-värde. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande Unicode-tecken. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Returnerar det angivna datumet och tiden. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Konverterar den angivna strängen till en instans av klassen [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen till en instans av klassen [DateTime](../datetime/) med den angivna formateringsinformationen. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inlåsta värdet till motsvarande [DateTime](../datetime/)-värde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Konverterar den angivna 8-bitars osignerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Konverterar det angivna dubbla talet till ett motsvarande decimaltal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Returnerar det angivna decimaltalet. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande [Decimal](../decimal/)-värde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Konverterar den angivna c-strängen som innehåller ett tal i textform till motsvarande [Decimal](../decimal/)-värde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande [Decimal](../decimal/)-värde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande [Decimal](../decimal/)-värde med den angivna formateringsinformationen. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande [Decimal](../decimal/)-värde med de angivna talstilarna och formateringsinformationen. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inloppade värdet till motsvarande [Decimal](../decimal/)-värde. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Konverterar den angivna 8-bitars osignerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Konverterar den angivna 16-bitars osignerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Konverterar den angivna 32-bitars osignerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Konverterar den angivna 64-bitars osignerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Konverterar det angivna enkelprecisionsnumret till ett motsvarande dubbelprecision flyttal. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Returnerar det angivna dubbla talet. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande dubbelprecision flyttal. |
| static **double** [ToDouble](./todouble/)(char_t) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande dubbelprecision flyttal. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Konverterar den angivna c-strängen som innehåller ett tal i textform till motsvarande dubbelprecision flyttal. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande dubbelprecision flyttal. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande dubbelprecision flyttal med den angivna formateringsinformationen. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande dubbelprecision flyttal med den angivna formateringsinformationen och talstilen. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inloppade värdet till ett dubbelprecision flyttal. Om typen av inloppat värde är [String](../string/) används det angivna strängformatet under konverteringen. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 16-bitars signerat heltal. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Konverterar den angivna 8-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Konverterar den angivna 16-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Returnerar det angivna 16-bitars signerade heltalet. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Konverterar den angivna 32-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Konverterar den angivna 64-bitars osignerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Konverterar det angivna dubbla talet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 16-bitars signerat heltal. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande 16-bitars heltalsvärde. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Konverterar den angivna c-strängen som innehåller ett tal i textform till motsvarande 16-bitars heltalsvärde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande 16-bitars heltalsvärde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller ett tal i textform i den angivna basen till motsvarande 16-bitars heltalsvärde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande 16-bitars heltalsvärde med den angivna formateringsinformationen. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller ett tal i textform till motsvarande 16-bitars heltalsvärde med den angivna formateringsinformationen och talstilen. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inloppade värdet till motsvarande 16-bitars heltal. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Konverterar den angivna 8-bitars osignerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Returnerar det angivna 32-bitars signerade heltal. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)(**float**) | Konverterar det angivna flyttalet (float) till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)(**double**) | Konverterar det angivna dubbelvärdet (double) till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 32-bitars signerat heltal. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 32-bitars signerat heltal. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande 32-bitars heltalsvärde. |
| static int [ToInt32](./toint32/)(const char_t *) | Konverterar den angivna C-strängen som innehåller talets teckenrepresentation till motsvarande 32-bitars heltalsvärde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 32-bitars heltalsvärde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande 32-bitars heltalsvärde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation med den angivna formateringsinformationen. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation med den angivna formateringsinformationen och talformat. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande 32-bitars heltalsvärde. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Konverterar det angivna boolska värdet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Returnerar det angivna 64-bitars signerade heltal. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Konverterar det angivna flyttalet (float) till ett motsvarande 64-bitars signerat heltal. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Konverterar det angivna dubbelvärdet (double) till ett motsvarande 64-bitars signerat heltal. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 64-bitars signerat heltal. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 64-bitars signerat heltal. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande 64-bitars heltalsvärde. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Konverterar den angivna C-strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalsvärde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 64-bitars heltalsvärde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande 64-bitars heltalsvärde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation med den angivna formateringsinformationen. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation med den angivna formateringsinformationen och talformat. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande 64-bitars heltalsvärde. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Konverterar det angivna boolska värdet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Returnerar det angivna 8-bitars signerade heltalet. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Konverterar det angivna flyttalet (float) till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Konverterar det angivna dubbelvärdet (double) till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 8-bitars signerat heltal. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande 8-bitars heltalsvärde. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Konverterar den angivna C-strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars heltalsvärde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars heltalsvärde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande 8-bitars heltalsvärde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 8-bitars heltal med den angivna formateringsinformationen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation med den angivna formateringsinformationen och talformat. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande 8-bitars heltalsvärde. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Konverterar det angivna boolska värdet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande enkelprecision flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande enkelprecisions flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande enkelprecisions flyttal. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Returnerar det angivna flyttalet. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Konverterar det angivna dubbelprecisions talet till ett motsvarande enkelprecisions flyttal. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande enkelprecisions flyttal. |
| static **float** [ToSingle](./tosingle/)(char_t) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande enkelprecisions flyttalsvärde. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Konverterar den angivna C-strängen som innehåller talets teckenrepresentation till motsvarande enkelprecisions flyttalsvärde. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande enkelprecisions flyttalsvärde. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande enkelprecisions flyttalsvärde med den angivna formateringsinformationen. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande enkelprecisions flyttalsvärde med den angivna formateringsinformationen och talformatet. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inlåsta värdet till ett enkelprecisions flyttalsvärde. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Konverterar det angivna värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till sträng med kulturspecifik formateringsinformation. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med den angivna strängformatet och kulturspecifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna värdet till dess strängrepresentation med det angivna strängformatet och kultur-specifik formateringsinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Konverterar det angivna värdet till sträng. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Konverterar det angivna värdet till sträng med det angivna strängformatet. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Konverterar den angivna arrayen av Unicode-tecken till sträng. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna arrayen av Unicode-tecken till sträng med den angivna kultur-specifika formateringsinformationen som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Returnerar det angivna värdet; ingen konvertering utförs. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Konverterar det angivna booleska värdet till dess strängrepresentation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Konverterar det angivna heltalsvärdet till dess strängrepresentation i den angivna basen. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Konverterar det angivna heltalsvärdet till dess strängrepresentation i den angivna basen. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Konverterar det angivna heltalsvärdet till dess strängrepresentation i den angivna basen. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Konverterar det angivna heltalsvärdet till dess strängrepresentation i den angivna basen. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inlåsta värdet till dess strängrepresentation. Om den inlåsta värdetypen är [String](../string/) används det angivna strängformatet vid konverteringen. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 16-bitars osignerat heltal. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Returnerar det angivna 16-bitars osignerade heltalet. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Konverterar det angivna flyttalet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimalvärdet till ett motsvarande 16-bitars osignerat heltal. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 16-bitars osignerat heltal. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande osignerade 16-bitars heltalsvärde. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Konverterar den angivna c-strängen som innehåller talets strängrepresentation till motsvarande osignerade 16-bitars heltalsvärde. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande osignerade 16-bitars heltalsvärde. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande osignerade 16-bitars heltalsvärde med den medföljande formateringsinformationen. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande osignerade 16-bitars heltalsvärde med den medföljande formateringsinformationen. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande osignerade 16-bitars heltalsvärde med den medföljande formateringsinformationen och talstilen. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna inlåsta värdet till motsvarande osignerat 16-bitars heltalsvärde. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 32-bitars osignerat heltal. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande 32-bitars osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande 32-bitars osignerat heltal. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande 32-bitars osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande 32-bitars osignerat heltal. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Returnerar det angivna 32-bitars osignerade heltalet. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Konverterar det angivna 32-bits signerade heltalet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Konverterar det angivna 64-bits osignerade heltalet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Konverterar det angivna 64-bits signerade heltalet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Konverterar det angivna dubbelvärdet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 32-bits osignerat heltal. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 32-bits osignerat heltal. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande osignerade 32-bits heltalsvärde. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Konverterar den angivna c-strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bits heltalsvärde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bits heltalsvärde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande osignerade 32-bits heltalsvärde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bits heltalsvärde med den medföljande formateringsinformationen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 32-bits heltalsvärde med den medföljande formateringsinformationen och talformat. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande osignerade 32-bits heltalsvärde. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Konverterar det angivna booleska värdet till ett motsvarande 64-bits osignerat heltal. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Konverterar det angivna 8-bits osignerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Konverterar det angivna 8-bits signerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Konverterar det angivna 16-bits osignerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Konverterar det angivna 16-bits signerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Konverterar det angivna 32-bits osignerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Konverterar det angivna 32-bits signerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Returnerar det angivna 64-bits osignerade heltalet. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Konverterar det angivna 64-bits signerade heltalet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Konverterar det angivna flyttalet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Konverterar det angivna dubbelvärdet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Konverterar det angivna decimaltalet till ett motsvarande 64-bits osignerat heltal. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Konverterar det angivna Unicode-tecknet till ett motsvarande 64-bits osignerat heltal. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Konvertering stöds inte. Kastar alltid InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Konverterar den angivna null-strängen till motsvarande osignerade 64-bits heltalsvärde. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Konverterar den angivna c-strängen som innehåller talets teckenrepresentation till motsvarande osignerade 64-bits heltalsvärde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 64-bits heltalsvärde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Konverterar den angivna strängen som innehåller talets teckenrepresentation i den angivna basen till motsvarande osignerade 64-bits heltalsvärde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 64-bits heltalsvärde med den medföljande formateringsinformationen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande osignerade 64-bits heltalsvärde med den medföljande formateringsinformationen och talformat. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar det angivna förpackade värdet till motsvarande osignerade 64-bits heltalsvärde. |
## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)