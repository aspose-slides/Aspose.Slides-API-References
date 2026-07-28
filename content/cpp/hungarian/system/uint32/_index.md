---
title: UInt32
second_title: Aspose.Slides C++ API referencia
description: Metódusokat tartalmaz a 32 bites előjel nélküli egész számmal való munkához.
type: docs
weight: 1977
url: /hu/system/uint32/
---
## UInt32 struktúra

Metódusokat tartalmaz a 32 bites előjel nélküli egész számmal való munkához.

```cpp
class UInt32
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 32 bites előjel nélküli egész számmá. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 32 bites előjel nélküli egész számmá a megadott formázási információk használatával. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 32 bites előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 32 bites előjel nélküli egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 32 bites előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)