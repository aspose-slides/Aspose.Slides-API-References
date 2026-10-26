---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列の要素を別の型にキャストします。
type: docs
weight: 2991
url: /ja/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) function

指定された配列の要素を別の型にキャストします。

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| To | 指定された配列の要素をキャストする型 |
| From | キャスト対象となる要素の型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | キャストする要素を含む配列への共有ポインタ |

### Return Value

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

非推奨
:   互換性のために追加されました。代わりに ExplicitCast を使用してください。

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)