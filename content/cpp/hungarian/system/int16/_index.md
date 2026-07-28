---
title: Int16
second_title: Aspose.Slides C++ API referencia
description: Metódusokat tartalmaz a 16 bites egész számmal való munkához.
type: docs
weight: 1028
url: /hu/system/int16/
---
## Int16 osztály

Tartalmaz olyan metódusokat, amelyekkel a 16 bites egész számmal dolgozhat.

```cpp
class Int16
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, az ekvivalens 16 bites előjeles egész számmá. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, az ekvivalens 16 bites előjeles egész számmá a megadott formázási információk használatával. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, az ekvivalens 16 bites előjeles egész számmá a megadott formázási információk és számstílus használatával. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, az ekvivalens 16 bites előjeles egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, az ekvivalens 16 bites előjeles egész számmá a megadott formázási információk és számstílus használatával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)