---
title: Double
second_title: Dokumentacja API Aspose.Slides dla C++
description: Zawiera metody umożliwiające pracę z liczbą zmiennoprzecinkową podwójnej precyzji.
type: docs
weight: 1574
url: /pl/system/double/
---
## Double struct

Zawiera metody umożliwiające pracę z liczbą zmiennoprzecinkową podwójnej precyzji.

```cpp
class Double
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji przy użyciu podanych informacji o formatowaniu. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji przy użyciu podanych informacji o formatowaniu oraz stylu liczby. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji przy użyciu podanych informacji o formatowaniu oraz stylu liczby. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

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