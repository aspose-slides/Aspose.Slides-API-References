---
title: Double
second_title: Aspose.Slides C++ API Referencia
description: Metódusokat tartalmaz a dupla pontosságú lebegőpontos szám kezeléséhez.
type: docs
weight: 1574
url: /hu/system/double/
---
## Double struktúra

Metódusokat tartalmaz a dupla pontosságú lebegőpontos szám kezeléséhez.

```cpp
class Double
```

## Módszerek

| Method | Description |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk felhasználásával. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk és számstílus felhasználásával. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk és számstílus felhasználásával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Mezők

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | A nullánál nagyobb legkisebb pozitív érték. |
| static constexpr [MaxValue](./maxvalue/) | A legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | A legkisebb lehetséges érték. |
| static constexpr [NaN](./nan/) | Nem szám érték. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatív végtelen. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Pozitív végtelen. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)