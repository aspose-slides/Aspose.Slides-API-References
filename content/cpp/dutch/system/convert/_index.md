---
title: Convert
second_title: Aspose.Slides voor C++ API-referentie
description: "De structuur die methoden bevat die conversie van waarden van het ene type naar waarden van een ander type uitvoeren. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr-klasse om objecten van dit type te beheren."
type: docs
weight: 1561
url: /nl/system/convert/
---
## Struct converteren


De structuur die methoden bevat die waarden van het ene type naar waarden van een ander type converteren. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Convert
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NIET GEÏMPLENTEERD. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Decodeert base-64 gecodeerde gegevens die worden weergegeven als een bereik in de array van Unicode-tekens. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Decodeert base-64 gecodeerde gegevens die worden weergegeven als een string. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Retourneert een TypeCode-waarde die het type van de opgegeven geïnboxte waarde weergeeft. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NIET GEÏMPLENTEERD. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NIET GEÏMPLENTEERD Valse implementatie, controleert of de waarde nullptr is. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Encodeert een bereik van elementen in de opgegeven byte-array met base-64 en slaat de gecodeerde gegevens op als een array van Unicode-tekens. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Encodeert een bereik van elementen in de opgegeven byte-array met base-64 en slaat de gecodeerde gegevens op als een array van Unicode-tekens. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Encodeert elementen in de opgegeven byte-array met base-64 en geeft de gecodeerde gegevens terug als een string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Encodeert een bereik van elementen in de opgegeven byte-array met base-64 en geeft de gecodeerde gegevens terug als een string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Encodeert elementen in de opgegeven byte-array met base-64 en geeft de gecodeerde gegevens terug als een string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Encodeert een bereik van elementen in de opgegeven byte-array met base-64 en geeft de gecodeerde gegevens terug als een string. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Retourneert de opgegeven booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Converteert het opgegeven 8-bit unsigned integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Converteert het opgegeven 8-bit signed integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Converteert het opgegeven 16-bit unsigned integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Converteert het opgegeven 16-bit signed integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Converteert het opgegeven 32-bit unsigned integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Converteert het opgegeven 32-bit signed integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Converteert het opgegeven 64-bit unsigned integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Converteert het opgegeven 64-bit signed integer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Converteert het opgegeven float-nummer naar een equivalente booleaanse waarde. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Converteert het opgegeven double-nummer naar een equivalente booleaanse waarde. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalente booleaanse waarde. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente booleaanse waarde. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Converteert de opgegeven C-string naar een bool-waarde. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Converteert de opgegeven string naar een bool-waarde. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string naar een bool-waarde. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven geïnboxte waarde naar een equivalente booleaanse waarde. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalent 8-bit unsigned integer. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Retourneert het opgegeven 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Converteert het opgegeven 8-bit signed integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Converteert het opgegeven 16-bit unsigned integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Converteert het opgegeven 16-bit signed integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Converteert het opgegeven 32-bit unsigned integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Converteert het opgegeven 32-bit signed integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Converteert het opgegeven 64-bit unsigned integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Converteert het opgegeven 64-bit signed integer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Converteert het opgegeven float-nummer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Converteert het opgegeven double-nummer naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Converteert het opgegeven Unicode-teken naar een equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente unsigned 8-bit integer-waarde. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Converteert de opgegeven C-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 8-bit integer-waarde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 8-bit integer-waarde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente unsigned 8-bit integer-waarde. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 8-bit integer-waarde met behulp van de meegegeven opmaakinformatie. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 8-bit integer-waarde met behulp van de meegegeven opmaakinformatie en getalstijl. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven geïnboxte waarde naar een equivalente unsigned 8-bit integer-waarde. |
| static char_t [ToChar](./tochar/)(**bool**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Converteert het opgegeven 8-bit unsigned integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Converteert het opgegeven 8-bit signed integer naar een equivalent Unicode-teken. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Converteert het opgegeven 16-bit unsigned integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Converteert het opgegeven 16-bit signed integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Converteert het opgegeven 32-bit unsigned integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Converteert het opgegeven 32-bit signed integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Converteert het opgegeven 64-bit unsigned integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Converteert het opgegeven 64-bit signed integer naar een equivalent Unicode-teken. |
| static char_t [ToChar](./tochar/)(**float**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Retourneert het opgegeven Unicode-teken. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Converteert het eerste en enige teken van de opgegeven C-string naar een char_t-waarde. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Converteert het eerste en enige teken van de opgegeven string naar een char_t-waarde. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert het eerste en enige teken van de opgegeven string naar een char_t-waarde. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven geïnboxte waarde naar een equivalente Unicode-teken. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Retourneert de opgegeven datum en tijd. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks naar een instantie van de [DateTime](../datetime/) klasse. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks naar een instantie van de [DateTime](../datetime/) klasse met behulp van de opgegeven opmaakinformatie. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente [DateTime](../datetime/) waarde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Converteert het opgegeven 8-bit ongetekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Converteert het opgegeven 8-bit ondertekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Converteert het opgegeven 16-bit ongetekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Converteert het opgegeven 16-bit ondertekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Converteert het opgegeven 32-bit ongetekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Converteert het opgegeven 32-bit ondertekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Converteert het opgegeven 64-bit ongetekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Converteert het opgegeven 64-bit ondertekende integer naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Converteert het opgegeven float-getal naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Converteert het opgegeven double-getal naar een equivalent decimaal getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Retourneert het opgegeven decimale getal. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente [Decimal](../decimal/) waarde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Converteert de opgegeven c-string met de tekenreeksrepresentatie van een getal naar de equivalente [Decimal](../decimal/) waarde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente [Decimal](../decimal/) waarde. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente [Decimal](../decimal/) waarde met behulp van de opgegeven opmaakinformatie. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente [Decimal](../decimal/) waarde met de opgegeven getalstijlen en opmaakinformatie. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente [Decimal](../decimal/) waarde. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Converteert het opgegeven 8-bit ongetekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Converteert het opgegeven 8-bit ondertekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Converteert het opgegeven 16-bit ongetekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Converteert het opgegeven 16-bit ondertekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Converteert het opgegeven 32-bit ongetekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Converteert het opgegeven 32-bit ondertekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Converteert het opgegeven 64-bit ongetekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Converteert het opgegeven 64-bit ondertekende integer naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Converteert het opgegeven single-precision getal naar een equivalent double-precisie floating-point getal. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Retourneert het opgegeven double-getal. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalent double-precisie floating-point getal. |
| static **double** [ToDouble](./todouble/)(char_t) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente double-precisie floating-point waarde. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Converteert de opgegeven c-string met de tekenreeksrepresentatie van een getal naar de equivalente double-precisie floating-point waarde. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente double-precisie floating-point waarde. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente double-precisie floating-point waarde met behulp van de opgegeven opmaakinformatie. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente double-precisie floating-point waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een double-precisie floating-point waarde. Als het type van de verpakte waarde [String](../string/) is, wordt het opgegeven tekenreeksformaat tijdens de conversie gebruikt. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalent 16-bit ondertekend integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Converteert het opgegeven 8-bit ongetekende integer naar een equivalent 16-bit ondertekend integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Converteert het opgegeven 8-bit ondertekende integer naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Converteert het opgegeven 16-bit ongetekende integer naar een equivalent 16-bit ondertekend integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Retourneert het opgegeven 16-bit ondertekende integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Converteert het opgegeven 32-bit ongetekende integer naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Converteert het opgegeven 32-bit ondertekende integer naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Converteert het opgegeven 64-bit ongetekende integer naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Converteert het opgegeven 64-bit ondertekende integer naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Converteert het opgegeven float-getal naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Converteert het opgegeven double-getal naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Converteert het opgegeven Unicode-teken naar een equivalent 16-bit ondertekend integer. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente 16-bit integer-waarde. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Converteert de opgegeven c-string met de tekenreeksrepresentatie van een getal naar de equivalente 16-bit integer-waarde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente 16-bit integer-waarde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal in de opgegeven basis naar de equivalente 16-bit integer-waarde. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente 16-bit integer-waarde met behulp van de opgegeven opmaakinformatie. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks met de tekenreeksrepresentatie van een getal naar de equivalente 16-bit integer-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente 16-bit integer-waarde. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalent 32-bit ondertekend integer. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Converteert het opgegeven 8-bit ongetekende integer naar een equivalent 32-bit ondertekend integer. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Converteert de opgegeven 8-bit ondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Converteert de opgegeven 16-bit onondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Converteert de opgegeven 16-bit ondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Converteert de opgegeven 32-bit onondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Retourneert de opgegeven 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Converteert de opgegeven 64-bit onondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(**int64_t**) | Converteert de opgegeven 64-bit ondertekende integer naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(**float**) | Converteert het opgegeven float-getal naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(**double**) | Converteert het opgegeven double-getal naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalente 32-bit ondertekende integer. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Converteert het opgegeven Unicode-teken naar een equivalente 32-bit ondertekende integer. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente 32-bit integerwaarde. |
| static int [ToInt32](./toint32/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bit integerwaarde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bit integerwaarde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 32-bit integerwaarde. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bit integerwaarde met gebruik van de opgegeven opmaakgegevens. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bit integerwaarde met gebruik van de opgegeven opmaakgegevens en getalstijl. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente 32-bit integerwaarde. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Converteert de opgegeven boolean-waarde naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Converteert de opgegeven 8-bit onondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Converteert de opgegeven 8-bit ondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Converteert de opgegeven 16-bit onondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Converteert de opgegeven 16-bit ondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Converteert de opgegeven 32-bit onondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Converteert de opgegeven 32-bit ondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Converteert de opgegeven 64-bit onondertekende integer naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Retourneert de opgegeven 64-bit ondertekende integer. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Converteert het opgegeven float-getal naar een equivalente 64-bit ondertekende integer. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Converteert het opgegeven double-getal naar een equivalente 64-bit ondertekende integer. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalente 64-bit ondertekende integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Converteert het opgegeven Unicode-teken naar een equivalente 64-bit ondertekende integer. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente int 64-bit integerwaarde. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integerwaarde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integerwaarde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 64-bit integerwaarde. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integerwaarde met gebruik van de opgegeven opmaakgegevens. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integerwaarde met gebruik van de opgegeven opmaakgegevens en getalstijl. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente 64-bit integerwaarde. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Converteert de opgegeven boolean-waarde naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Converteert de opgegeven 8-bit onondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Retourneert de opgegeven 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Converteert de opgegeven 16-bit onondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Converteert de opgegeven 16-bit ondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Converteert de opgegeven 32-bit onondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Converteert de opgegeven 32-bit ondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Converteert de opgegeven 64-bit onondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Converteert de opgegeven 64-bit ondertekende integer naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Converteert het opgegeven float-getal naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Converteert het opgegeven double-getal naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Converteert het opgegeven Unicode-teken naar een equivalente 8-bit ondertekende integer. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente 8-bit integerwaarde. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit integerwaarde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit integerwaarde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 8-bit integerwaarde. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente onondertekende 8-bit integerwaarde met gebruik van de opgegeven opmaakgegevens. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit integerwaarde met gebruik van de opgegeven opmaakgegevens en getalstijl. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente 8-bit integerwaarde. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Converteert de opgegeven boolean-waarde naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Converteert de opgegeven 8-bit onondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Converteert de opgegeven 8-bit ondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Converteert de opgegeven 16-bit onondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Converteert de opgegeven 16-bit ondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Converteert de opgegeven 32-bit onondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Converteert de opgegeven 32-bit ondertekende integer naar een equivalent enkelprecisie zwevendekommagetal. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Converteert het opgegeven 64-bit unsigned integer naar een gelijkwaardige single-precision floating-point-waarde. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Converteert het opgegeven 64-bit signed integer naar een gelijkwaardige single-precision floating-point-waarde. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Retourneert het opgegeven float-getal. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Converteert het opgegeven double-precision getal naar een gelijkwaardige single-precision floating-point-waarde. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een gelijkwaardige single-precision floating-point-waarde. |
| static **float** [ToSingle](./tosingle/)(char_t) | Conversie wordt niet ondersteund. Werpt altijd InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Werpt altijd InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Converteert de opgegeven null-string naar de gelijkwaardige single-precision floating-point-waarde. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige single-precision floating-point-waarde. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige single-precision floating-point-waarde. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige single-precision floating-point-waarde met behulp van de verstrekte opmaakinformatie. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige single-precision floating-point-waarde met behulp van de verstrekte opmaakinformatie en getalstijl. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een single-precision floating-point-waarde. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar een string met cultuur-specifieke opmaakinformatie. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuur-specifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/)-object. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven waarde naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Converteert de opgegeven waarde naar een tekenreeks. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Converteert de opgegeven waarde naar een tekenreeks met behulp van het opgegeven tekenreeksformaat. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Converteert de opgegeven array van Unicode-tekens naar een tekenreeks. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven array van Unicode-tekens naar een tekenreeks met behulp van de opgegeven cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Retourneert de opgegeven waarde; er wordt geen conversie uitgevoerd. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Converteert de opgegeven booleaanse waarde naar zijn tekenreeksrepresentatie. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Converteert de opgegeven gehele getalwaarde naar zijn tekenreeksrepresentatie in de opgegeven basis. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Converteert de opgegeven gehele getalwaarde naar zijn tekenreeksrepresentatie in de opgegeven basis. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Converteert de opgegeven gehele getalwaarde naar zijn tekenreeksrepresentatie in de opgegeven basis. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Converteert de opgegeven gehele getalwaarde naar zijn tekenreeksrepresentatie in de opgegeven basis. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar zijn tekenreeksrepresentatie. Als het type van de verpakte waarde [String](../string/) is, wordt het opgegeven tekenreeksformaat tijdens de conversie gebruikt. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalente 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Converteert de opgegeven 8-bit unsigned integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Converteert de opgegeven 8-bit signed integer naar een equivalente 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Retourneert de opgegeven 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Converteert de opgegeven 16-bit signed integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Converteert de opgegeven 32-bit unsigned integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Converteert de opgegeven 32-bit signed integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Converteert de opgegeven 64-bit unsigned integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Converteert de opgegeven 64-bit signed integer naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Converteert het opgegeven float-getal naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Converteert het opgegeven double-getal naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimal-getal naar een equivalente 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Converteert het opgegeven Unicode-karakter naar een equivalente 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Werpt altijd InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Converteert de opgegeven null-string naar de equivalente unsigned 16-bit integer-waarde. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 16-bit integer-waarde. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 16-bit integer-waarde. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente unsigned 16-bit integer-waarde. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 16-bit integer-waarde met behulp van de opgegeven opmaakinformatie. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 16-bit integer-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven verpakte waarde naar een equivalente unsigned 16-bit integer-waarde. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een equivalente 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Converteert de opgegeven 8-bit unsigned integer naar een equivalente 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Converteert de opgegeven 8-bit signed integer naar een equivalente 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Converteert de opgegeven 16-bit unsigned integer naar een equivalente 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Converteert de opgegeven 16-bit signed integer naar een equivalente 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Retourneert de opgegeven 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Converteert het opgegeven 32-bit ondertekende geheel getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Converteert het opgegeven 64-bit ongetekende geheel getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Converteert het opgegeven 64-bit ondertekende geheel getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Converteert het opgegeven float getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Converteert het opgegeven double getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Converteert het opgegeven unicode teken naar een gelijkwaardig 32-bit ongetekend geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Converteert de opgegeven null-string naar de gelijkwaardige unsigned 32-bit integer-waarde. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige unsigned 32-bit integer-waarde. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde met behulp van de opgegeven opmaakinformatie. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven ingepakte waarde naar een gelijkwaardige unsigned 32-bit integer-waarde. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een gelijkwaardig 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Converteert het opgegeven 8-bit unsigned integer naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Converteert het opgegeven 8-bit ondertekende integer naar een gelijkwaardig 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Converteert het opgegeven 16-bit unsigned integer naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Converteert het opgegeven 16-bit ondertekende integer naar een gelijkwaardig 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Converteert het opgegeven 32-bit unsigned integer naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Converteert het opgegeven 32-bit ondertekende integer naar een gelijkwaardig 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Retourneert het opgegeven 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Converteert het opgegeven 64-bit ondertekende integer naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Converteert het opgegeven float getal naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Converteert het opgegeven double getal naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Converteert het opgegeven decimale getal naar een gelijkwaardig 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Converteert het opgegeven unicode teken naar een gelijkwaardig 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Conversie wordt niet ondersteund. Gooit altijd InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Converteert de opgegeven null-string naar de gelijkwaardige unsigned 64-bit integer-waarde. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 64-bit integer-waarde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 64-bit integer-waarde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige unsigned 64-bit integer-waarde. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 64-bit integer-waarde met behulp van de opgegeven opmaakinformatie. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 64-bit integer-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven ingepakte waarde naar een gelijkwaardige unsigned 64-bit integer-waarde. |
## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)