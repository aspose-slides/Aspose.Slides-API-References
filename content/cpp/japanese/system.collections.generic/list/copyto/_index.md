---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: リスト要素を既存の配列要素にコピーします。
type: docs
weight: 209
url: /ja/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) method


リスト要素を既存の配列要素にコピーします。

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | コピー先の配列。 |
| arrayIndex | int | コピー先配列の開始インデックス。 |

## List::CopyTo(const System::ArrayPtr\<T\>\&) method


すべての要素を既存の配列要素にコピーします。

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) に要素をコピーする。 |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) method


指定されたインデックスから始めて要素を既存の配列要素にコピーします。

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 現在のオブジェクトが表すリスト内の要素の、コピー開始位置となる 0 ベースのインデックス。 |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) に要素をコピーする。 |
| arrayIndex | int | コピー先配列の開始位置。 |
| count | int | コピーする要素数。 |

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [List](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)