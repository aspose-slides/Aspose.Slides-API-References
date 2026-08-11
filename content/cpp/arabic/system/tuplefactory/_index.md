---
title: TupleFactory
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر طرقًا ثابتة لإنشاء كائنات tuple.
type: docs
weight: 1366
url: /ar/system/tuplefactory/
---
## TupleFactory فئة

يوفر طرقًا ثابتة لإنشاء كائنات tuple.

```cpp
class TupleFactory
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | ينشئ كائن tuple جديد. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | ينشئ 8-tuple جديد. العنصر الثامن يُخزن داخل [Tuple](../tuple/). |
## ملاحظات



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
هذا المثال البرمجي ينتج الإخراج التالي:
العنصر 1: 256
العنصر 2: 16
العنصر 3: 64
*/
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)