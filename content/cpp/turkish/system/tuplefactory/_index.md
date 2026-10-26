---
title: TupleFactory
second_title: Aspose.Slides for C++ API Referansı
description: Tuple nesneleri oluşturmak için statik yöntemler sağlar.
type: docs
weight: 1366
url: /tr/system/tuplefactory/
---
## TupleFactory sınıfı

Tuple nesneleri oluşturmak için statik yöntemler sağlar.

```cpp
class TupleFactory
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Yeni bir tuple nesnesi oluşturur. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Yeni bir 8-tuple oluşturur. 8. öğe [Tuple](../tuple/) içinde depolanır. |
## Açıklamalar



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Öge 1: 256
Öge 2: 16
Öge 3: 64
*/
```

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)