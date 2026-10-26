---
title: Double
second_title: Aspose.Slides için C++ API Referansı
description: Double hassasiyetli kayan nokta sayısı ile çalışmak için yöntemler içerir.
type: docs
weight: 1574
url: /tr/system/double/
---
## Double yapısı

double hassasiyetli kayan nokta sayısı ile çalışmak için yöntemler içerir.

```cpp
class Double
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen sayının dize temsilini içeren metni eşdeğer double hassasiyetli kayan nokta değerine dönüştürür. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren metni, sağlanan biçimlendirme bilgilerini kullanarak eşdeğer double hassasiyetli kayan nokta değerine dönüştürür. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren metni, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer double hassasiyetli kayan nokta değerine dönüştürür. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Belirtilen sayının dize temsilini içeren metni eşdeğer double hassasiyetli kayan nokta değerine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Belirtilen sayının dize temsilini içeren metni, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer double hassasiyetli kayan nokta değerine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Sıfırdan büyük en küçük pozitif değer. |
| static constexpr [MaxValue](./maxvalue/) | Mümkün olan en büyük değer. |
| static constexpr [MinValue](./minvalue/) | Mümkün olan en küçük değer. |
| static constexpr [NaN](./nan/) | sayı olmayan değer. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatif sonsuz. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Pozitif sonsuz. |

## Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)