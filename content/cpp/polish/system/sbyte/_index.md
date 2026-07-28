---
title: SByte
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zawiera metody do pracy z 8-bitową liczbą całkowitą.
type: docs
weight: 1873
url: /pl/system/sbyte/
---
## SByte struktura

Zawiera metody do pracy z 8-bitową liczbą całkowitą.

```cpp
class SByte
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem, używając podanych informacji o formatowaniu. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem, używając podanych informacji o formatowaniu i stylu liczby. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą ze znakiem, używając podanych informacji o formatowaniu i stylu liczby. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Największa możliwa wartość. |
| static constexpr [MinValue](./minvalue/) | Najmniejsza możliwa wartość. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)