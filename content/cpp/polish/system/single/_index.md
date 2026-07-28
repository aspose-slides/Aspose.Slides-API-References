---
title: Single
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zawiera metody umożliwiające pracę z liczbą zmiennoprzecinkową o pojedynczej precyzji.
type: docs
weight: 1899
url: /pl/system/single/
---
## Single struct

Zawiera metody umożliwiające pracę z liczbą zmiennoprzecinkową o pojedynczej precyzji.

```cpp
class Single
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną wartość zmiennoprzecinkową o pojedynczej precyzji. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną wartość zmiennoprzecinkową o pojedynczej precyzji przy użyciu podanych informacji formatowania. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną wartość zmiennoprzecinkową o pojedynczej precyzji przy użyciu podanych informacji formatowania i stylu liczby. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną wartość zmiennoprzecinkową o pojedynczej precyzji. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Konwertuje określony ciąg zawierający reprezentację liczby w postaci tekstowej na równoważną wartość zmiennoprzecinkową o pojedynczej precyzji przy użyciu podanych informacji formatowania i stylu liczby. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Najmniejsza dodatnia wartość większa od zera. |
| static constexpr [MaxValue](./maxvalue/) | Największa możliwa wartość. |
| static constexpr [MinValue](./minvalue/) | Najmniejsza możliwa wartość. |
| static constexpr [NaN](./nan/) | Wartość, która nie jest liczbą. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Ujemna nieskończoność. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Dodatnia nieskończoność. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)