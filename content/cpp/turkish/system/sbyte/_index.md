---
title: SByte
second_title: Aspose.Slides for C++ API Referansı
description: 8-bit tamsayıyla çalışmak için yöntemler içerir.
type: docs
weight: 1873
url: /tr/system/sbyte/
---
## SByte struct

8-bit tamsayıyla çalışmak için yöntemler içerir.

```cpp
class SByte
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen sayının dize temsili içeren dizeyi eşdeğer 8-bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 8-bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak eşdeğer 8-bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Belirtilen sayının dize temsili içeren dizeyi eşdeğer 8-bit işaretli tamsayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak eşdeğer 8-bit işaretli tamsayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Olabilecek en büyük değer. |
| static constexpr [MinValue](./minvalue/) | Olabilecek en küçük değer. |

## Ayrıca Bakınız

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)