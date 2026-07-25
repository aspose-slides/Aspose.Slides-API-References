---
title: Clear()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す配列は読み取り専用のため、サポートされていません。
type: docs
weight: 53
url: /ja/system/array/clear/
---
## Array::Clear() メソッド


現在のオブジェクトが表す配列は読み取り専用であるため、サポートされていません。

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) メソッド


指定された配列の **startIndex** インデックスから **count** 個の値を既定値に置き換えます。

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Type | Type of elements in the target array |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |
| startIndex | int | [Index](../../index/) で置換を開始するインデックス |
| count | int | 置換する項目数 |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)