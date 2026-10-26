---
title: UInt64
second_title: Aspose.Slides için C++ API Referansı
description: İşaretsiz 64 bit tamsayı ile çalışmak için yöntemler içerir.
type: docs
weight: 1990
url: /tr/system/uint64/
---
## UInt64 yapısı

İşaretsiz 64 bit tamsayı ile çalışmak için yöntemler içerir.

```cpp
class UInt64
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak, bir sayının dize temsilini içeren belirtilen dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak, bir sayının dize temsilini içeren belirtilen dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak, bir sayının dize temsilini içeren belirtilen dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Mümkün olan en büyük değer. |
| static constexpr [MinValue](./minvalue/) | Mümkün olan en küçük değer. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)