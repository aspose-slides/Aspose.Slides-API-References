---
title: Int64
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zawiera metody umożliwiające pracę z 64-bitową liczbą całkowitą.
type: docs
weight: 1054
url: /pl/system/int64/
---
## Klasa Int64

Zawiera metody umożliwiające pracę z 64-bitową liczbą całkowitą.

```cpp
class Int64
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem za pomocą podanych informacji o formatowaniu. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem za pomocą podanych informacji o formatowaniu i stylu liczby. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | Konwertuje określony ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową liczbę całkowitą ze znakiem za pomocą podanych informacji o formatowaniu i stylu liczby. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Największa możliwa wartość. |
| static constexpr [MinValue](./minvalue/) | Najmniejsza możliwa wartość. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)