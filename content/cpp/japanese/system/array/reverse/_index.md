---
title: Reverse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列の要素を逆順にします。
type: docs
weight: 755
url: /ja/system/array/reverse/
---
## Array::Reverse(const ArrayPtr\<Type\>\&) メソッド


指定された配列の要素の順序を逆にします。

```cpp
template<typename Type> static void System::Array<T>::Reverse(const ArrayPtr<Type> &arr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |

## Array::Reverse(const ArrayPtr\<Type\>\&, int, int) メソッド


指定された配列の要素の範囲の順序を逆にします。

```cpp
template<typename Type> static void System::Array<T>::Reverse(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |
| startIndex | int | 逆転する範囲の開始位置となる[Index](../../index/) |
| count | int | 逆転する範囲のサイズ |

## 関連項目

* 型定義 [ArrayPtr](../../arrayptr/)
* メソッド [Type](../../object/type/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)