---
title: Create()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的元組物件。
type: docs
weight: 1
url: /zh-hant/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) 方法

建立一個新的元組物件。

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) 方法

建立一個新的 8 元組。第 8 個元素儲存在 [Tuple](../../tuple/) 中。

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Tuple](../../tuple/)
* 類別 [TupleFactory](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)