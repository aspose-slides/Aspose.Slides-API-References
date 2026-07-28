---
title: SByte
second_title: Aspose.Slides C++ API-referencia
description: Metódusokat tartalmaz a 8 bites egész számok kezeléséhez.
type: docs
weight: 1873
url: /hu/system/sbyte/
---
## SByte struct

Metódusokat tartalmaz a 8 bites egész számok kezeléséhez.

```cpp
class SByte
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá a megadott formázási információk felhasználásával. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá a megadott formázási információk és számtípus felhasználásával. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá a megadott formázási információk és számtípus felhasználásával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)