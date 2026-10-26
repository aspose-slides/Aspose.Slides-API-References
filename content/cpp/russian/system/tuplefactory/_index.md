---
title: TupleFactory
second_title: Aspose.Slides для C++: справочник API
description: Предоставляет статические методы для создания объектов кортежа.
type: docs
weight: 1340
url: /ru/system/tuplefactory/
---
## TupleFactory класс

Предоставляет статические методы для создания объектов кортежа.

```cpp
class TupleFactory
```

## Методы

| Метод | Описание |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Создаёт новый объект кортежа. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Создаёт новый 8-кортеж. 8-й элемент хранится внутри [Tuple](../tuple/). |
## Примечания



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
Этот пример кода выводит следующее:
Элемент 1: 256
Элемент 2: 16
Элемент 3: 64
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)