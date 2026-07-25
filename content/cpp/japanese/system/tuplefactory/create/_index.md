---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいタプルオブジェクトを作成します。
type: docs
weight: 1
url: /ja/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) メソッド


新しいタプルオブジェクトを作成します。

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) メソッド


新しい8タプルを作成します。8番目の要素は[Tuple](../../tuple/)に格納されます。

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Tuple](../../tuple/)
* クラス [TupleFactory](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)