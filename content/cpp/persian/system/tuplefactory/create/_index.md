---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء تاپل جدید ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) method

یک شیء تاپل جدید ایجاد می‌کند.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) method

یک ۸-تاپل جدید ایجاد می‌کند. عنصر هشتم در داخل [Tuple](../../tuple/) ذخیره می‌شود.

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## موارد مرتبط

* نوع‌تعریف [SharedPtr](../../sharedptr/)
* کلاس [Tuple](../../tuple/)
* کلاس [TupleFactory](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)