---
title: Boolean
second_title: Aspose.Slides for C++ API Referansı
description: System.Boolean .Net tipinin sabit üyelerini tutan sınıf.
type: docs
weight: 79
url: /tr/system/boolean/
---
## Boolean sınıfı

Sabit üyeleri [System.Boolean](./) .[Net](../../system.net/) tipinde tutan sınıf.

```cpp
class Boolean
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen dizeyi bool tipinde bir değere dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Belirtilen dizeyi bool tipinde bir değere dönüştürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) 'false' boolean değerinin temsili. |
| static [TrueString](./truestring/) | [String](../string/) 'true' boolean değerinin temsili. |

## Açıklamalar



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Boolean değişkenini oluştur.
  bool isWeekend = false;

  // Girdi dizesini ayrıştır ve sonucu yazdır.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Hafta sonu: Evet
*/
```

## Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)