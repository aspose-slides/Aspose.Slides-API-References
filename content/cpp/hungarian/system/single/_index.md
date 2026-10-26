---
title: Single
second_title: Aspose.Slides C++ API Referencia
description: Metódusokat tartalmaz az egyszeres pontosságú lebegőpontos számmal való munkához.
type: docs
weight: 1899
url: /hu/system/single/
---
## Egyetlen struktúra

Metódusokat tartalmaz az egyszeres pontosságú lebegőpontos szám kezeléséhez.

```cpp
class Single
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az egyenértékű egyszeres pontosságú lebegőpontos értékké. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az egyenértékű egyszeres pontosságú lebegőpontos értékké a megadott formázási információk alapján. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az egyenértékű egyszeres pontosságú lebegőpontos értékké a megadott formázási információk és számformátum alapján. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az egyenértékű egyszeres pontosságú lebegőpontos értékké. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az egyenértékű egyszeres pontosságú lebegőpontos értékké a megadott formázási információk és számformátum alapján. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Legkisebb pozitív érték, amely nagyobb, mint nulla. |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |
| static constexpr [NaN](./nan/) | Nem szám érték. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatív végtelen. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Pozitív végtelen. |

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)