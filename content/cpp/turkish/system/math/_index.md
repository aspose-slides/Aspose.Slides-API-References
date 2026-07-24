---
title: Math
second_title: Aspose.Slides for C++ API Referansı
description: Matematik fonksiyonları içerir. Bu, örnek hizmeti olmayan statik bir türdür. Hiçbir şekilde onun örneklerini oluşturmayınız.
type: docs
weight: 1782
url: /tr/system/math/
---
## Math yapısı


Matematik fonksiyonları içerir. Bu, statik bir türdür ve örnek hizmeti yoktur. Hiçbir koşulda onun örneklerini oluşturmayınız.

```cpp
class Math
```

## Metotlar

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Belirtilen değerin mutlak değerini döndürür. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Belirtilen [Decimal](../decimal/) nesnesi tarafından temsil edilen değerin mutlak değerini döndürür. |
| static **double** [Acos](./acos/)(**double**) | Belirtilen değerin arkkosinüsünü hesaplar. |
| static **double** [Asin](./asin/)(**double**) | Belirtilen değerin arcsinini hesaplar. |
| static **double** [Atan](./atan/)(**double**) | Belirtilen değerin arktanjantını hesaplar. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Belirtilen değerlerin oranının arktanjantını hesaplar. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | İki 32-bit tamsayının tam çarpımını döndürür. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Belirtilen değerden büyük veya eşit olan en küçük tam sayıyı döndürür. |
| static **double** [Ceiling](./ceiling/)(**double**) | Belirtilen değerden büyük veya eşit olan en küçük tam sayıyı döndürür. |
| static **double** [Cos](./cos/)(**double**) | Belirtilen değerin kosinüsünü hesaplar. |
| static **double** [Cosh](./cosh/)(**double**) | Belirtilen değerin hiperbolik kosinüsünü hesaplar. |
| static int [DivRem](./divrem/)(int, int, int\&) | İki 32-bit tamsayının bölümünü ve kalanını hesaplar. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | İki 64-bit tamsayının bölümünü ve kalanını hesaplar. |
| static **double** [Exp](./exp/)(**double**) | Belirtilen üssün e sabitiyle yükseltilmiş değerini döndürür. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Belirtilen değerden küçük veya eşit olan en büyük tam sayıyı döndürür. |
| static **double** [Floor](./floor/)(**double**) | Belirtilen değerden küçük veya eşit olan en büyük tam sayıyı döndürür. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Belirtilen bir sayının başka bir belirtilen sayı ile bölünmesinden kalan değeri döndürür. |
| static **double** [Log](./log/)(**double**) | Belirtilen değerin doğal logaritmasını döndürür. |
| static **double** [Log](./log/)(**double**, **double**) | Belirtilen değerin belirtilen tabanda logaritmasını döndürür. |
| static **double** [Log10](./log10/)(**double**) | Belirtilen değerin taban-10 logaritmasını döndürür. |
| static auto [Max](./max/)(T0, T1) | Belirtilen iki sayısal değerden en büyüğünü döndürür. |
| static T0 [Max](./max/)(T0, T1) | Belirtilen iki sayısal değerden en büyüğünü döndürür. |
| **float** [Max_](./max_/)(**float**, **float**) | Belirtilen iki değerden en büyük tek duyarlıklı kayan nokta değerini döndürür. |
| **double** [Max_](./max_/)(**double**, **double**) | Belirtilen iki değerden en büyük çift duyarlıklı kayan nokta değerini döndürür. |
| static auto [Min](./min/)(T0, T1) | Belirtilen iki sayısal değerden en küçüğünü döndürür. |
| static T0 [Min](./min/)(T0, T1) | Belirtilen iki sayısal değerden en küçüğünü döndürür. |
| **float** [Min_](./min_/)(**float**, **float**) | Belirtilen iki değerden en küçük tek duyarlıklı kayan nokta değerini döndürür. |
| **double** [Min_](./min_/)(**double**, **double**) | Belirtilen iki değerden en küçük çift duyarlıklı kayan nokta değerini döndürür. |
| static T [Modulus](./modulus/)(T, T) | Belirtilen bir değerin başka bir değer ile bölünmesinden kalan değeri hesaplar. |
| static **double** [Pow](./pow/)(**double**, **double**) | Belirtilen değeri belirtilen üssüne yükseltir ve döndürür. |
| static **double** [Round](./round/)(**double**) | Belirtilen değeri en yakın tam sayıya yuvarlar. |
| static **double** [Round](./round/)(**double**, int) | Belirtilen değeri belirtilen ondalık basamak sayısına sahip en yakın değere yuvarlar. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirli değerin iki en yakın sayıya eşit uzaklıkta olması durumunda fonksiyonun davranışını belirler. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri belirtilen ondalık basamak sayısına sahip en yakın değere yuvarlar. Bir parametre, belirli değerin iki en yakın sayıya eşit uzaklıkta olması durumunda fonksiyonun davranışını belirler. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Belirtilen değeri en yakın tam sayıya yuvarlar. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Belirtilen değeri belirtilen ondalık basamak sayısına sahip en yakın değere yuvarlar. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirli değerin iki en yakın sayıya eşit uzaklıkta olması durumunda fonksiyonun davranışını belirler. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri belirtilen ondalık basamak sayısına sahip en yakın değere yuvarlar. Bir parametre, belirli değerin iki en yakın sayıya eşit uzaklıkta olması durumunda fonksiyonun davranışını belirler. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Belirtilen işaretli tam sayının işaretini belirler. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Belirtilen kayan nokta değerinin işaretini belirler. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık değerin işaretini belirler. |
| static **double** [Sin](./sin/)(**double**) | Belirtilen değerin sinüsünü hesaplar. |
| static **double** [Sinh](./sinh/)(**double**) | Belirtilen değerin hiperbolik sinüsünü hesaplar. |
| static **double** [Sqrt](./sqrt/)(**double**) | Belirtilen değerin karekökünü döndürür. |
| static **double** [Tan](./tan/)(**double**) | Belirtilen değerin tanjantını hesaplar. |
| static **double** [Tanh](./tanh/)(**double**) | Belirtilen değerin hiperbolik tanjantını hesaplar. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Belirtilen [Decimal](../decimal/) nesnesi tarafından temsil edilen değerin bütün ondalık basamakları atıldıktan sonra tam kısmı eşit olan [Decimal](../decimal/) nesnesini döndürür. |
| static **double** [Truncate](./truncate/)(**double**) | Belirtilen değerin bütün ondalık basamakları atıldıktan sonra tam kısmı eşit olan çift duyarlıklı kayan nokta değerini döndürür. |

## Alanlar

| Field | Description |
| --- | --- |
| static [E](./e/) | Doğal logaritmanın tabanı. |
| static [NaN](./nan/) | NaN (Not-a-Number) değerini temsil eder. |
| static [NegativeInfinity](./negativeinfinity/) | Negatif sonsuzluğu temsil eder. |
| static [PI](./pi/) | Pi sayısının sabiti. |
| static [PositiveInfinity](./positiveinfinity/) | Pozitif sonsuzluğu temsil eder. |

## Açıklamalar



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Mutlak değerleri yazdır.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // PI/2'nin sinüsünü ve PI'nin kosinüsünü yazdır.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## İlgili

* Namespace [System](../)
* Library [Aspose.Slides](../../)