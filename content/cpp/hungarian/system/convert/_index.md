---
title: Convert
second_title: Aspose.Slides C++ API referencia
description: "Az a struktúra, amely olyan metódusokat tartalmaz, amelyek egy típusú értékek átalakítását egy másik típusú értékké végzik. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1561
url: /hu/system/convert/
---
## Struktúra konvertálása


Az a struktúra, amely olyan metódusokat tartalmaz, amelyek egy típusú értékeket egy másik típusú értékké konvertálják. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Convert
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NEM IMPLEMENTÁLVA. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Dekódolja a base-64 kódolt adatot, amely Unicode karakterek tömbjében lévő tartományként van ábrázolva. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Dekódolja a base-64 kódolt adatot, amely egy karakterláncként van ábrázolva. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Visszaad egy TypeCode értéket, amely a megadott dobozolt érték típusát jelöli. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NEM IMPLEMENTÁLVA. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NEM IMPLEMENTÁLVA Hamis implementáció, ellenőrzi, hogy az érték nullptr-e. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Base-64 kódol egy elemtartományt a megadott bájtarray-ban, és a kódolt adatot Unicode karakterek tömbjeként tárolja. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kódol egy elemtartományt a megadott bájtarray-ban, és a kódolt adatot Unicode karakterek tömbjeként tárolja. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Base-64 kódolja az elemeket a megadott bájtarray-ban, és a kódolt adatot karakterláncként adja vissza. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Base-64 kódol egy elemtartományt a megadott bájtarray-ban, és a kódolt adatot karakterláncként adja vissza. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kódolja az elemeket a megadott bájtarray-ban, és a kódolt adatot karakterláncként adja vissza. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kódol egy elemtartományt a megadott bájtarray-ban, és a kódolt adatot karakterláncként adja vissza. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Visszaadja a megadott logikai értéket. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Átalakítja a megadott lebegőpontos számot ekvivalens logikai értékké. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Átalakítja a megadott dupla pontosságú lebegőpontos számot ekvivalens logikai értékké. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot ekvivalens logikai értékké. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Átalakítja a megadott null-stringet ekvivalens logikai értékké. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Átalakítja a megadott C-stringet logikai (bool) típusú értékké. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot logikai (bool) típusú értékké. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot logikai (bool) típusú értékké. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket ekvivalens logikai értékké. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Átalakítja a megadott logikai értéket ekvivalens 8 bites előjel nélküli egész számmá. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Visszaadja a megadott 8 bites előjel nélküli egész számot. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Átalakítja a megadott lebegőpontos számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Átalakítja a megadott dupla pontosságú lebegőpontos számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Átalakítja a megadott Unicode karaktert ekvivalens 8 bites előjel nélküli egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Átalakítja a megadott null-stringet ekvivalens előjel nélküli 8 bites egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Átalakítja a megadott C-stringet, amely szám ábrázolását tartalmazza, ekvivalens előjel nélküli 8 bites egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely szám ábrázolását tartalmazza, ekvivalens előjel nélküli 8 bites egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám ábrázolását tartalmazza a megadott alapon, ekvivalens előjel nélküli 8 bites egész számmá. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely szám ábrázolását tartalmazza, ekvivalens előjel nélküli 8 bites egész számmá a megadott formázási információk felhasználásával. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely szám ábrázolását tartalmazza, ekvivalens előjel nélküli 8 bites egész számmá a megadott formázási információk és számformátum felhasználásával. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket ekvivalens előjel nélküli 8 bites egész számmá. |
| static char_t [ToChar](./tochar/)(**bool**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot ekvivalens Unicode karakterré. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot ekvivalens Unicode karakterré. |
| static char_t [ToChar](./tochar/)(**float**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static char_t [ToChar](./tochar/)(**double**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Visszaadja a megadott Unicode karaktert. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static char_t [ToChar](./tochar/)(const char_t *) | Átalakítja a megadott C-string első és egyetlen karakterét char_t értékké. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Átalakítja a megadott karakterlánc első és egyetlen karakterét char_t értékké. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterlánc első és egyetlen karakterét char_t értékké. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket ekvivalens Unicode karakterré. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Az átalakítás nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Visszaadja a megadott dátumot és időt. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot a(z) [DateTime](../datetime/) osztály egy példányává. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot a(z) [DateTime](../datetime/) osztály egy példányává a megadott formázási információk felhasználásával. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket az ekvivalens [DateTime](../datetime/) értékké. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Átalakítja a megadott lebegőpontos számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Átalakítja a megadott dupla pontosságú számot egy ekvivalens decimális számmá. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Visszaadja a megadott decimális számot. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot az ekvivalens [Decimal](../decimal/) értékké. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Átalakítja a megadott c-karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens [Decimal](../decimal/) értékké. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens [Decimal](../decimal/) értékké. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens [Decimal](../decimal/) értékké a megadott formázási információk felhasználásával. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens [Decimal](../decimal/) értékké a megadott számstílusok és formázási információk felhasználásával. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket az ekvivalens [Decimal](../decimal/) értékké. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Átalakítja a megadott egyszeres pontosságú számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Visszaadja a megadott dupla számot. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy ekvivalens dupla pontosságú lebegőpontos számmá. |
| static **double** [ToDouble](./todouble/)(char_t) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot az ekvivalens dupla pontosságú lebegőpontos értékké. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Átalakítja a megadott c-karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk felhasználásával. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk és számstílus felhasználásával. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket dupla pontosságú lebegőpontos értékké. Ha a dobozolt érték típusa [String](../string/), akkor a megadott karakterláncformátumot használja a konverzió során. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 16 bites előjeles egész számmá. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Visszaadja a megadott 16 bites előjeles egész számot. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Átalakítja a megadott lebegőpontos számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Átalakítja a megadott dupla számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Átalakítja a megadott Unicode karaktert egy ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot az ekvivalens 16 bites egész értékké. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Átalakítja a megadott c-karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites egész értékké. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites egész értékké. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites egész értékké a megadott számrendszerben. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites egész értékké a megadott formázási információk felhasználásával. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites egész értékké a megadott formázási információk és számstílus felhasználásával. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket az ekvivalens 16 bites egész értékké. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Visszaadja a megadott 32 bites előjeles egész számot. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy ekvivalens 32 bites előjeles egész számmá. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Átalakítja a megadott Unicode karaktert egy ekvivalens 32 bites előjeles egész számmá. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const char_t *) | Átalakítja a megadott c-stringet, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását a megadott számrendszerben tartalmazza, egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk felhasználásával egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk és számstílus felhasználásával egy ekvivalens 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egy ekvivalens 32 bites egész értékké. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Visszaadja a megadott 64 bites előjeles egész számot. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 64 bites előjeles egész számmá. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 64 bites előjeles egész számmá. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy ekvivalens 64 bites előjeles egész számmá. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Átalakítja a megadott Unicode karaktert egy ekvivalens 64 bites előjeles egész számmá. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Átalakítja a megadott c-stringet, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását a megadott számrendszerben tartalmazza, egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk felhasználásával egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk és számstílus felhasználásával egy ekvivalens 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egy ekvivalens 64 bites egész értékké. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Visszaadja a megadott 8 bites előjeles egész számot. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Átalakítja a megadott Unicode karaktert egy ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot egy ekvivalens 8 bites egész értékké. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Átalakítja a megadott c-stringet, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 8 bites egész értékké. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, egy ekvivalens 8 bites egész értékké. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását a megadott számrendszerben tartalmazza, egy ekvivalens 8 bites egész értékké. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk felhasználásával egy ekvivalens előjel nélküli 8 bites egész számmá. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megadott formázási információk és számstílus felhasználásával egy ekvivalens 8 bites egész értékké. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egy ekvivalens 8 bites egész értékké. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens egyszeres pontosságú lebegőpontos számra. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy megfelelő egyszeres pontosságú lebegőpontos számmá. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy megfelelő egyszeres pontosságú lebegőpontos számmá. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Visszaadja a megadott float számot. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Átalakítja a megadott dupla pontosságú számot egy megfelelő egyszeres pontosságú lebegőpontos számmá. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott decimális számot egy megfelelő egyszeres pontosságú lebegőpontos számmá. |
| static **float** [ToSingle](./tosingle/)(char_t) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot egy megfelelő egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Átalakítja a megadott c-karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, egy megfelelő egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, egy megfelelő egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megadott formázási információk használatával egy megfelelő egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megadott formázási információk és számstílus használatával egy megfelelő egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egyszeres pontosságú lebegőpontos értékké. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Átalakítja a megadott értéket a karakterlánc ábrázolásává. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket karakterlánccá a kultúraspecifikus formázási információk használatával. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásává a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásával a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásával a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásával a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásával a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a karakterlánc ábrázolásával a megadott karakterformátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk felhasználásával. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Átalakítja a megadott értéket a megadott karakterlánc formátum segítségével sztringgé. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Átalakítja a megadott Unicode karakterek tömbjét sztringgé. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott Unicode karakterek tömbjét a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk felhasználásával sztringgé. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Visszaadja a megadott értéket; nincs konverzió. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Átalakítja a megadott értéket sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Átalakítja a megadott egész szám értékét a megadott alap szerint sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Átalakítja a megadott egész szám értékét a megadott alap szerint sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Átalakítja a megadott egész szám értékét a megadott alap szerint sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Átalakítja a megadott egész szám értékét a megadott alap szerint sztringgé. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket sztringgé. Ha a dobozolt érték típusa [String](../string/), a megadott karakterlánc formátumot használja a konverzió során. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Átalakítja a megadott 8 bites előjelű egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Visszaadja a megadott 16 bites előjel nélküli egész számot. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Átalakítja a megadott 16 bites előjelű egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Átalakítja a megadott 32 bites előjelű egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Átalakítja a megadott 64 bites előjelű egész számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott tizedes számot egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Átalakítja a megadott Unicode karaktert egy ekvivalens 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Átalakítja a megadott null-úri karakterláncot az ekvivalens előjel nélküli 16 bites egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Átalakítja a megadott C-karakterláncot, amely szám szöveges ábrázolását tartalmazza, az ekvivalens előjel nélküli 16 bites egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely szám szöveges ábrázolását tartalmazza, az ekvivalens előjel nélküli 16 bites egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza a megadott alapban, az ekvivalens előjel nélküli 16 bites egész számmá. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely szám szöveges ábrázolását tartalmazza, az ekvivalens előjel nélküli 16 bites egész számmá a megadott formázási információk felhasználásával. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely szám szöveges ábrázolását tartalmazza, az ekvivalens előjel nélküli 16 bites egész számmá a megadott formázási információk és számstílus felhasználásával. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket ekvivalens előjel nélküli 16 bites egész számmá. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Átalakítja a megadott 8 bites előjelű egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Átalakítja a megadott 16 bites előjelű egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Visszaadja a megadott 32 bites előjel nélküli egész számot. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott tizedes számot egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Átalakítja a megadott unicode karaktert egy ekvivalens 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot az ekvivalens előjel nélküli 32 bites egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Átalakítja a megadott c-stringet, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 32 bites egész szám értékévé. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 32 bites egész szám értékévé. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza a megadott számrendszerben, az ekvivalens előjel nélküli 32 bites egész szám értékévé. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 32 bites egész szám értékévé a megadott formázási információk felhasználásával. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 32 bites egész szám értékévé a megadott formázási információk és számformátum felhasználásával. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egy ekvivalens előjel nélküli 32 bites egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Átalakítja a megadott logikai értéket egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Visszaadja a megadott 64 bites előjel nélküli egész számot. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Átalakítja a megadott float számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Átalakítja a megadott double számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Átalakítja a megadott tizedes számot egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Átalakítja a megadott unicode karaktert egy ekvivalens 64 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | A konverzió nem támogatott. Mindig InvalidCastException-t dob. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Átalakítja a megadott null-karakterláncot az ekvivalens előjel nélküli 64 bites egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Átalakítja a megadott c-stringet, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 64 bites egész szám értékévé. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 64 bites egész szám értékévé. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza a megadott számrendszerben, az ekvivalens előjel nélküli 64 bites egész szám értékévé. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 64 bites egész szám értékévé a megadott formázási információk felhasználásával. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens előjel nélküli 64 bites egész szám értékévé a megadott formázási információk és számformátum felhasználásával. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott dobozolt értéket egy ekvivalens előjel nélküli 64 bites egész számmá. |
## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)