---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的元组对象。
type: docs
weight: 1
url: /zh/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) 方法


创建一个新的元组对象。

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```
## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) 方法


创建一个新的 8 元组。第 8 个元素存储在 [Tuple](../../tuple/) 中。

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## 另请参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [Tuple](../../tuple/)
* 类 [TupleFactory](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)