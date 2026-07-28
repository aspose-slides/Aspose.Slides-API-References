---
title: UInt64
second_title: Aspose.Slides C++ API referenciája
description: Metódusokat tartalmaz, amelyekkel a 64-bit előjel nélküli egész számmal dolgozhat.
type: docs
weight: 1990
url: /hu/system/uint64/
---
## UInt64 struct

Metódusokat tartalmaz, amelyekkel a 64 bit előjel nélküli egész számmal dolgozhat.

```cpp
class UInt64
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott, egy szám szöveges ábrázolását tartalmazó karakterláncot a megfelelő 64 bit előjel nélküli egész számmá. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott, egy szám szöveges ábrázolását tartalmazó karakterláncot a megfelelő 64 bit előjel nélküli egész számmá a megadott formázási információk használatával. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott, egy szám szöveges ábrázolását tartalmazó karakterláncot a megfelelő 64 bit előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Átalakítja a megadott, egy szám szöveges ábrázolását tartalmazó karakterláncot a megfelelő 64 bit előjel nélküli egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Átalakítja a megadott, egy szám szöveges ábrázolását tartalmazó karakterláncot a megfelelő 64 bit előjel nélküli egész számmá a megadott formázási információk és számstílus használatával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)