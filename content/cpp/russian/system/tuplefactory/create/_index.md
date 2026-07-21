---
title: Create()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый объект кортежа.
type: docs
weight: 1
url: /ru/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) метод

Создает новый объект кортежа.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) метод

Создает новый 8-кортеж. 8-й элемент хранится внутри [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Tuple](../../tuple/)
* Класс [TupleFactory](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)