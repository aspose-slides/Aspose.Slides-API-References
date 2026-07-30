---
title: Convert
second_title: Reference API Aspose.Slides pro C++
description: "Struktura, která obsahuje metody provádějící konverzi hodnot jednoho typu na hodnoty jiného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 1561
url: /cs/system/convert/
---
## Struktura konverze

Struktura, která obsahuje metody provádějící konverzi hodnot jednoho typu na hodnoty jiného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k řízení objektů tohoto typu.

```cpp
class Convert
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NEIMPLEMENTOVÁNO. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Dekóduje data kódovaná base-64 reprezentovaná jako rozsah v poli znaků Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Dekóduje data kódovaná base-64 reprezentovaná jako řetězec. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Vrací hodnotu TypeCode reprezentující typ zadané zabalené hodnoty. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NEIMPLEMENTOVÁNO. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NEIMPLEMENTOVÁNO Falešná implementace, kontroluje, zda je hodnota nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Kóduje base-64 rozsah prvků ve specifikovaném byte poli a uloží zakódovaná data jako pole znaků Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Kóduje base-64 rozsah prvků ve specifikovaném byte poli a uloží zakódovaná data jako pole znaků Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Kóduje base-64 prvky ve specifikovaném byte poli a vrací zakódovaná data jako řetězec. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Kóduje base-64 rozsah prvků ve specifikovaném byte poli a vrací zakódovaná data jako řetězec. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Kóduje base-64 prvky ve specifikovaném byte poli a vrací zakódovaná data jako řetězec. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Kóduje base-64 rozsah prvků ve specifikovaném byte poli a vrací zakódovaná data jako řetězec. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Vrací zadanou booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Převádí zadané 8bitové nezáporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Převádí zadané 8bitové záporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Převádí zadané 16bitové nezáporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Převádí zadané 16bitové záporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Převádí zadané 32bitové nezáporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Převádí zadané 32bitové záporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Převádí zadané 64bitové nezáporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Převádí zadané 64bitové záporné celé číslo na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Převádí zadané číslo typu float na ekvivalentní booleovskou hodnotu. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Převádí zadané číslo typu double na ekvivalentní booleovskou hodnotu. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní booleovskou hodnotu. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Převádí zadaný null-string na ekvivalentní booleovskou hodnotu. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Převádí zadaný C-string na hodnotu typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Převádí zadaný řetězec na hodnotu typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec na hodnotu typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní booleovskou hodnotu. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Převádí zadanou booleovskou hodnotu na ekvivalentní 8-bitové nezáporné celé číslo. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Vrací zadané 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Převádí zadané 8-bitové záporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Převádí zadané 16-bitové nezáporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Převádí zadané 16-bitové záporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Převádí zadané 32-bitové nezáporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Převádí zadané 32-bitové záporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Převádí zadané 64-bitové nezáporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Převádí zadané 64-bitové záporné celé číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Převádí zadané číslo typu float na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Převádí zadané číslo typu double na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Převádí zadaný znak Unicode na ekvivalentní 8-bitové nezáporné celé číslo. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Převádí zadaný null-string na ekvivalentní hodnotu unsigned 8-bitového celého čísla. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Převádí zadaný C-string obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu unsigned 8-bitového celého čísla. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu unsigned 8-bitového celého čísla. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla v určeném základu na ekvivalentní hodnotu unsigned 8-bitového celého čísla. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu unsigned 8-bitového celého čísla pomocí poskytnutých formátovacích informací. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu unsigned 8-bitového celého čísla pomocí poskytnutých formátovacích informací a stylu čísla. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní unsigned 8-bitovou celočíselnou hodnotu. |
| static char_t [ToChar](./tochar/)(**bool**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Převádí zadané 8-bitové nezáporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Převádí zadané 8-bitové záporné celé číslo na ekvivalentní znak Unicode. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Převádí zadané 16-bitové nezáporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Převádí zadané 16-bitové záporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Převádí zadané 32-bitové nezáporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Převádí zadané 32-bitové záporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Převádí zadané 64-bitové nezáporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Převádí zadané 64-bitové záporné celé číslo na ekvivalentní znak Unicode. |
| static char_t [ToChar](./tochar/)(**float**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Vrací zadaný znak Unicode. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Převádí první a jediný znak zadaného C-stringu na hodnotu typu char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Převádí první a jediný znak zadaného řetězce na hodnotu typu char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí první a jediný znak zadaného řetězce na hodnotu typu char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní znak Unicode. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Vrací zadané datum a čas. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Převádí zadaný řetězec na instanci třídy [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec na instanci třídy [DateTime](../datetime/) pomocí poskytnutých informací o formátování. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní hodnotu [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Převádí zadanou boolean hodnotu na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Převádí zadané 8-bitové neznaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Převádí zadané 8-bitové znaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Převádí zadané 16-bitové neznaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Převádí zadané 16-bitové znaménkové celé číslo na ekvariantní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Převádí zadané 32-bitové neznaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Převádí zadané 32-bitové znaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Převádí zadané 64-bitové neznaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Převádí zadané 64-bitové znaménkové celé číslo na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Převádí zadané číslo typu float na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Převádí zadané číslo typu double na ekvivalentní desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Vrací zadané desítkové číslo. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Převádí zadaný nulový řetězec na ekvivalentní hodnotu [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Převádí zadaný c-řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu [Decimal](../decimal/) pomocí poskytnutých informací o formátování. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu [Decimal](../decimal/) pomocí zadaných stylů čísel a informací o formátování. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní hodnotu [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Převádí zadanou boolean hodnotu na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Převádí zadané 8-bitové neznaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Převádí zadané 8-bitové znaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Převádí zadané 16-bitové neznaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Převádí zadané 16-bitové znaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Převádí zadané 32-bitové neznaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Převádí zadané 32-bitové znaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Převádí zadané 64-bitové neznaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Převádí zadané 64-bitové znaménkové celé číslo na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Převádí zadané číslo typu float na ekvivalentní číslo s dvojitou přesností. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Vrací zadané číslo typu double. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní číslo s dvojitou přesností. |
| static **double** [ToDouble](./todouble/)(char_t) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Převádí zadaný nulový řetězec na ekvivalentní hodnotu typu double s dvojitou přesností. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Převádí zadaný c-řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu typu double s dvojitou přesností. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu typu double s dvojitou přesností. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu typu double s dvojitou přesností pomocí poskytnutých informací o formátování. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní hodnotu typu double s dvojitou přesností pomocí poskytnutých informací o formátování a stylu čísla. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na číslo typu double s dvojitou přesností. Pokud je typ zabalené hodnoty [String](../string/), použije se při konverzi zadaný řetězcový formát. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Převádí zadanou boolean hodnotu na ekvivalentní 16-bitové znaménkové celé číslo. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Převádí zadané 8-bitové neznaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Převádí zadané 8-bitové znaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Převádí zadané 16-bitové neznaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Vrací zadané 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Převádí zadané 32-bitové neznaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Převádí zadané 32-bitové znaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Převádí zadané 64-bitové neznaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Převádí zadané 64-bitové znaménkové celé číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Převádí zadané číslo typu float na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Převádí zadané číslo typu double na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Převádí zadaný znak Unicode na ekvivalentní 16-bitové znaménkové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Převádí zadaný nulový řetězec na ekvivalentní 16-bitové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Převádí zadaný c-řetězec obsahující řetězcové vyjádření čísla na ekvivalentní 16-bitové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní 16-bitové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla v zadaném základu na ekvivalentní 16-bitové celé číslo. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní 16-bitové celé číslo pomocí poskytnutých informací o formátování. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující řetězcové vyjádření čísla na ekvivalentní 16-bitové celé číslo pomocí poskytnutých informací o formátování a stylu čísla. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní 16-bitové celé číslo. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Převádí zadanou boolean hodnotu na ekvivalentní 32-bitové znaménkové celé číslo. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Převádí zadané 8-bitové neznaménkové celé číslo na ekvivalentní 32-bitové znaménkové celé číslo. |

| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Převede zadané 8-bitové celé číslo se znaménkem na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Převede zadané 16-bitové celé číslo bez znaménka na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Převede zadané 16-bitové celé číslo se znaménkem na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Převede zadané 32-bitové celé číslo bez znaménka na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Vrací zadané 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Převede zadané 64-bitové celé číslo bez znaménka na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(**int64_t**) | Převede zadané 64-bitové celé číslo se znaménkem na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(**float**) | Převede zadané číslo typu float na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(**double**) | Převede zadané číslo typu double na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Převede zadané desetinné číslo na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Převede zadaný znak Unicode na ekvivalentní 32-bitové celé číslo se znaménkem. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Převede zadaný nulový řetězec na ekvivalentní 32-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const char_t *) | Převede zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Převede zadaný řetězec obsahující textovou reprezentaci čísla v zadané soustavě na ekvivalentní 32-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací a stylu čísla. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou zabalenou hodnotu na ekvivalentní 32-bitovou celočíselnou hodnotu. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Převede zadanou logickou hodnotu na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Převede zadané 8-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Převede zadané 8-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Převede zadané 16-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Převede zadané 16-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Převede zadané 32-bitové celé číslo bez znaménka na ekvariantní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Převede zadané 32-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Převede zadané 64-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Vrací zadané 64-bitové celé číslo se znaménkem. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Převede zadané číslo typu float na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Převede zadané číslo typu double na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Převede zadané desetinné číslo na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Převede zadaný znak Unicode na ekvivalentní 64-bitové celé číslo se znaménkem. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Převede zadaný nulový řetězec na ekvivalentní 64-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Převede zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Převede zadaný řetězec obsahující textovou reprezentaci čísla v zadané soustavě na ekvivalentní 64-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací a stylu čísla. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou zabalenou hodnotu na ekvivalentní 64-bitovou celočíselnou hodnotu. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Převede zadanou logickou hodnotu na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Převede zadané 8-bitové celé číslo bez znaménka na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Vrací zadané 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Převede zadané 16-bitové celé číslo bez znaménka na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Převede zadané 16-bitové celé číslo se znaménkem na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Převede zadané 32-bitové celé číslo bez znaménka na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Převede zadané 32-bitové celé číslo se znaménkem na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Převede zadané 64-bitové celé číslo bez znaménka na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Převede zadané 64-bitové celé číslo se znaménkem na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Převede zadané číslo typu float na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Převede zadané číslo typu double na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Převede zadané desetinné číslo na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Převede zadaný znak Unicode na ekvivalentní 8-bitové celé číslo se znaménkem. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Převede zadaný nulový řetězec na ekvivalentní 8-bitovou celočíselnou hodnotu. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Převede zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitovou celočíselnou hodnotu. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitovou celočíselnou hodnotu. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Převede zadaný řetězec obsahující textovou reprezentaci čísla v zadané soustavě na ekvivalentní 8-bitovou celočíselnou hodnotu. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní nezápornou 8-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitovou celočíselnou hodnotu pomocí poskytnutých formátovacích informací a stylu čísla. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou zabalenou hodnotu na ekvivalentní 8-bitovou celočíselnou hodnotu. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Převede zadanou logickou hodnotu na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Převede zadané 8-bitové celé číslo bez znaménka na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Převede zadané 8-bitové celé číslo se znaménkem na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Převede zadané 16-bitové celé číslo bez znaménka na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Převede zadané 16-bitové celé číslo se znaménkem na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Převede zadané 32-bitové celé číslo bez znaménka na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Převede zadané 32-bitové celé číslo se znaménkem na ekvivalentní číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Převede zadané 64-bitové celé číslo bez znaménka na ekvivalentní číslo s jednoduchou přesností (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Převede zadané 64-bitové celé číslo se znaménkem na ekvivalentní číslo s jednoduchou přesností (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Vrátí zadané číslo typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Převede zadané číslo s dvojitou přesností na ekvivalentní číslo s jednoduchou přesností (float). |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Převede zadané desetinné číslo na ekvivalentní číslo s jednoduchou přesností (float). |
| static **float** [ToSingle](./tosingle/)(char_t) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Převede zadaný null-string na ekvivalentní hodnotu typu float. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Převede zadaný c-string obsahující textové vyjádření čísla na ekvivalentní hodnotu typu float. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní hodnotu typu float. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní hodnotu typu float pomocí poskytnutých informací o formátování. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní hodnotu typu float pomocí poskytnutých informací o formátování a stylu čísla. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou obalenou hodnotu na hodnotu typu float. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Převede zadanou hodnotu na její řetězcové vyjádření. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na řetězec pomocí informací o formátování specifických pro kulturu. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcové vyjádření pomocí zadaného formátu řetězce a informací o formátování specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci pomocí zadaného formátu řetězce a kulturně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Převede zadanou hodnotu na řetězec. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Převede zadanou hodnotu na řetězec pomocí zadaného formátu řetězce. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Převede zadané pole Unicode znaků na řetězec. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadané pole Unicode znaků na řetězec pomocí zadaných kulturálně specifických informací o formátování poskytnutých zadaným objektem [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Vrátí zadanou hodnotu; není provedena žádná konverze. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Převede zadanou hodnotu na její řetězcovou reprezentaci. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Převede zadanou celočíselnou hodnotu na její řetězcovou reprezentaci ve zvoleném číselném základě. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Převede zadanou celočíselnou hodnotu na její řetězcovou reprezentaci ve zvoleném číselném základě. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Převede zadanou celočíselnou hodnotu na její řetězcovou reprezentaci ve zvoleném číselném základě. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Převede zadanou celočíselnou hodnotu na její řetězcovou reprezentaci ve zvoleném číselném základě. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou zabalenou hodnotu na její řetězcovou reprezentaci. Pokud je typ zabalené hodnoty [String](../string/), během konverze se použije zadaný formát řetězce. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Vrátí zadané 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaměnkа. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Převede zadanou boolovskou hodnotu na ekvivalentní 16-bitové číslo bez znaménka. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Převede zadaný unicode znak na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Převod není podporován. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Převede zadaný null-string na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Převede zadaný c-string obsahující řetězcovou reprezentaci čísla na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla v zadaném základu na ekvivalentní 16-bitové číslo bez znaménka. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 16-bitové číslo bez znaménka pomocí poskytnutých informací o formátování. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 16-bitové číslo bez znaménka pomocí poskytnutých informací o formátování a číslicovém stylu. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadanou zabalenou hodnotu na ekvivalentní číslo bez znaménka o šířce 16 bitů. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Převede zadanou boolovskou hodnotu na ekvivalentní 32-bitové číslo bez znaménka. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 32-bitové číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 32-bitové číslo bez znaménka. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 32-bitové číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Převede zadanou boolovskou hodnotu na ekvivalentní 32-bitové číslo bez znaménka. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Vrátí zadané 32-bitové číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Převádí zadané 32-bitové celé číslo se znaménkem na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Převádí zadané 64-bitové celé číslo bez znaménka na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Převádí zadané 64-bitové celé číslo se znaménkem na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Převádí zadané číslo typu float na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Převádí zadané číslo typu double na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Převádí zadaný znak Unicode na ekvivalentní 32-bitové celé číslo bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Převádí zadaný nulový řetězec na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Převádí zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla v daném základu na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvariantní 32-bitovou celočíselnou hodnotu bez znaménka pomocí poskytnutých formátovacích informací. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka pomocí poskytnutých formátovacích informací a stylu čísel. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní 32-bitovou celočíselnou hodnotu bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Převádí zadanou booleovskou hodnotu na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Převádí zadané 8-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Převádí zadané 8-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Převádí zadané 16-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Převádí zadané 16-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Převádí zadané 32-bitové celé číslo bez znaménka na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Převádí zadané 32-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Vrací zadané 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Převádí zadané 64-bitové celé číslo se znaménkem na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Převádí zadané číslo typu float na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Převádí zadané číslo typu double na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Převádí zadané desítkové číslo na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Převádí zadaný znak Unicode na ekvivalentní 64-bitové celé číslo bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Konverze není podporována. Vždy vyvolá výjimku InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Převádí zadaný nulový řetězec na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Převádí zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla v daném základu na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka pomocí poskytnutých formátovacích informací. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka pomocí poskytnutých formátovacích informací a stylu čísel. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadanou zabalenou hodnotu na ekvivalentní 64-bitovou celočíselnou hodnotu bez znaménka. |
## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)