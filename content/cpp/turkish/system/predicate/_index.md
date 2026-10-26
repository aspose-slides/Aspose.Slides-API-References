---
title: Predicate
second_title: Aspose.Slides for C++ API Referansı
description: Bir koşula işaretçi - tek bir argüman kabul eden ve bir bool değeri döndüren çağırılabilir bir varlığı temsil eder.
type: docs
weight: 4187
url: /tr/system/predicate/
---
## Predicate tip tanımı

Bir koşula işaretçi, yani tek bir argüman kabul eden ve bir bool değeri döndüren çağırılabilir bir varlığı temsil eder.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Açıklamalar

```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Diziyi doldur.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // 3'ten büyük bir dizi öğesi döndüren koşulu oluştur.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Oluşturulan koşulu kullanarak dizinin ilk öğesini bulun ve yazdır.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
5
*/
```

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)