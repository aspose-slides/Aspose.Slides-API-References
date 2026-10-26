---
title: CombineMode
second_title: Aspose.Slides için C++ API Referansı
description: Kırpma bölgelerinin nasıl birleştirildiğini belirtir.
type: docs
weight: 170
url: /tr/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Kırpma bölgelerinin nasıl birleştirileceğini belirtir.

```cpp
enum class CombineMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Replace | 0 | Bir kırpma bölgesi diğer biriyle değiştirilir. |
| Intersect | 1 | İki kırpma bölgesi, kesişimleri alınarak birleştirilir. |
| Union | 2 | İki kırpma bölgesi, her ikisinin birleşimi alınarak birleştirilir. |
| Xor | 3 | İki kırpma bölgesi, yalnızca bir bölge ya da diğer bölge tarafından çevrelenen alan alınarak birleştirilir, ancak ikisi birden değil. |
| Exclude | 4 | İki kırpma bölgesi, birinci bölgenin ikinciyle kesişmeyen alanı alınarak birleştirilir. |
| Complement | 5 | İki kırpma bölgesi, ikinci bölgenin birincisiyle kesişmeyen alanı alınarak birleştirilir. |

## Ayrıca Bakınız

* İsim Alanı [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)