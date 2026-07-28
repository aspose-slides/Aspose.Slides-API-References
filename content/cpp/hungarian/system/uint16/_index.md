---
title: UInt16
second_title: Aspose.Slides C++ API referenciája
description: Metódusokat tartalmaz a 16 bites előjel nélküli egész szám kezelésére.
type: docs
weight: 1964
url: /hu/system/uint16/
---
## UInt16 struct

Metódusokat tartalmaz a 16 bites előjel nélküli egész szám kezelésére.

```cpp
class UInt16
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megfelelő 16 bites előjel nélküli egész számmá. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megfelelő 16 bites előjel nélküli egész számmá a megadott formázási információk használatával. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megfelelő 16 bites előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megfelelő 16 bites előjel nélküli egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | Átalakítja a megadott karakterláncot, amely a szám szöveges ábrázolását tartalmazza, a megfelelő 16 bites előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)