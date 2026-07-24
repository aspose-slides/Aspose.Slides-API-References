---
title: Single
second_title: Aspose.Slides için C++ API Referansı
description: Tek duyarlıklı kayan nokta sayısı ile çalışmak için yöntemler içerir.
type: docs
weight: 1899
url: /tr/system/single/
---
## Tek struct

Tek duyarlıklı kayan nokta sayısı ile çalışmak için yöntemler içerir.

```cpp
class Single
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen sayıyı temsil eden dizeyi, eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayıyı temsil eden dizeyi, sağlanan biçimlendirme bilgilerini kullanarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayıyı temsil eden dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Belirtilen sayıyı temsil eden dizeyi, eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Belirtilen sayıyı temsil eden dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Sıfırdan büyük en küçük pozitif değer. |
| static constexpr [MaxValue](./maxvalue/) | Alınabilecek en büyük değer. |
| static constexpr [MinValue](./minvalue/) | Alınabilecek en küçük değer. |
| static constexpr [NaN](./nan/) | Sayı olmayan değer. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatif sonsuz. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Pozitif sonsuz. |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.Slides](../../)