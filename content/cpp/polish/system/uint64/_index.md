---
title: UInt64
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zawiera metody do pracy z nieoznaczoną 64-bitową liczbą całkowitą.
type: docs
weight: 1990
url: /pl/system/uint64/
---
## UInt64 struct

Zawiera metody do pracy z nieoznaczonym 64-bitowym liczbą całkowitą.

```cpp
class UInt64
```

## Metody

| Method | Description |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje podany ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową nieoznaczoną liczbę całkowitą. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową nieoznaczoną liczbę całkowitą, używając podanych informacji o formatowaniu. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową nieoznaczoną liczbę całkowitą, używając podanych informacji o formatowaniu i stylu liczby. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Konwertuje podany ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową nieoznaczoną liczbę całkowitą. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Konwertuje podany ciąg zawierający tekstową reprezentację liczby na równoważną 64-bitową nieoznaczoną liczbę całkowitą, używając podanych informacji o formatowaniu i stylu liczby. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Pola

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Największa możliwa wartość. |
| static constexpr [MinValue](./minvalue/) | Najmniejsza możliwa wartość. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)