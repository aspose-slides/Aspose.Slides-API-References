---
title: TupleFactory
second_title: مرجع API Aspose.Slides برای C++
description: روش‌های ایستا برای ایجاد اشیاء تاپل فراهم می‌کند.
type: docs
weight: 1366
url: /fa/system/tuplefactory/
---
## TupleFactory کلاس

روش‌های ایستا برای ایجاد اشیاء تاپل فراهم می‌کند.

```cpp
class TupleFactory
```

## متدها

| متد | توضیح |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | یک شیء تاپل جدید ایجاد می‌کند. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | یک 8-تاپل جدید ایجاد می‌کند. عنصر هشتم در داخل [Tuple](../tuple/) ذخیره می‌شود. |

## توضیحات

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
این مثال کد خروجی زیر را تولید می‌کند:
آیتم 1: 256
آیتم 2: 16
آیتم 3: 64
*/
```

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)