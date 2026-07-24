---
title: MathF
second_title: Aspose.Slides for C++ API Referansı
description: Tek duyarlıklı kayan nokta değerleri için matematik fonksiyonları içerir. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde örnekleri oluşturulmamalıdır.
type: docs
weight: 1795
url: /tr/system/mathf/
---
## MathF yapısı

Tek duyarlıklı kayan nokta değerleri için matematik fonksiyonları içerir. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde örnekleri oluşturulmamalıdır.

```cpp
class MathF
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static T [Abs](./abs/)(T) | Belirtilen değerin mutlak değerini döndürür. |
| static **float** [Acos](./acos/)(**float**) | Belirtilen değerin arccosinusunu hesaplar. |
| static **float** [Asin](./asin/)(**float**) | Belirtilen değerin arcsinini hesaplar. |
| static **float** [Atan](./atan/)(**float**) | Belirtilen değerin arktanjantını hesaplar. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Belirtilen değerlerin oranının arktanjantını hesaplar. |
| static **float** [Ceiling](./ceiling/)(**float**) | Belirtilen değerden büyük veya ona eşit en küçük tam sayıyı döndürür. |
| static **float** [Cos](./cos/)(**float**) | Belirtilen değerin kosinüsünü hesaplar. |
| static **float** [Cosh](./cosh/)(**float**) | Belirtilen değerin hiperbolik kosinüsünü hesaplar. |
| static **float** [Exp](./exp/)(**float**) | e sabitinin belirtilen üsse yükseltilmiş değerini döndürür. |
| static **float** [Floor](./floor/)(**float**) | Belirtilen değerden küçük veya ona eşit en büyük tam sayıyı döndürür. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Belirtilen bir sayının başka bir sayı ile bölünmesinden kalan değeri döndürür. |
| static **float** [Log](./log/)(**float**) | Belirtilen değerin doğal logaritmasını döndürür. |
| static **float** [Log](./log/)(**float**, **float**) | Belirtilen değerin belirtilen tabandaki logaritmasını döndürür. |
| static **float** [Log10](./log10/)(**float**) | Belirtilen değerin taban-10 logaritmasını döndürür. |
| static **float** [Pow](./pow/)(**float**, **float**) | Belirtilen değeri belirtilen üsse yükseltir. |
| static **float** [Round](./round/)(**float**) | Belirtilen değeri en yakın tam sayıya yuvarlar. |
| static **float** [Round](./round/)(**float**, int) | Belirtilen değeri belirtilen sayıdaki kesirli basamağa yuvarlar. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, değer iki en yakın sayıya eşit uzaklıkta olduğunda fonksiyonun davranışını belirler. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri belirtilen sayıdaki kesirli basamağa yuvarlar. Bir parametre, değer iki en yakın sayıya eşit uzaklıkta olduğunda fonksiyonun davranışını belirler. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri belirtilen sayıdaki kesirli basamağa yuvarlar. Bir parametre, değer iki en yakın sayıya eşit uzaklıkta olduğunda fonksiyonun davranışını belirler. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Belirtilen işaretli tam sayı değerinin işaretini belirler. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Belirtilen kayan nokta değerinin işaretini belirler. |
| static **float** [Sin](./sin/)(**float**) | Belirtilen değerin sinüsünü hesaplar. |
| static **float** [Sinh](./sinh/)(**float**) | Belirtilen değerin hiperbolik sinüsünü hesaplar. |
| static **float** [Sqrt](./sqrt/)(**float**) | Belirtilen değerin karekökünü döndürür. |
| static **float** [Tan](./tan/)(**float**) | Belirtilen değerin tanjantını hesaplar. |
| static **float** [Tanh](./tanh/)(**float**) | Belirtilen değerin hiperbolik tanjantını hesaplar. |
| static **float** [Truncate](./truncate/)(**float**) | Tüm kesirli basamakları atılmış, tam kısmı belirtilen değere eşit bir float hassasiyetli kayan nokta değeri döndürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [E](./e/) | Doğal logaritmanın tabanı. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Pi sayısı sabiti. |
| static [Tau](./tau/) | Tau değeri. |

## Ayrıca Bakınız

* İsim alanı [System](../)
* Kütüphane [Aspose.Slides](../../)