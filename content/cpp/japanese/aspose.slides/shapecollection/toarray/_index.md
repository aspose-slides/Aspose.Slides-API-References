---
title: ToArray()
second_title: Aspose.Slides for C++ APIリファレンス
description: すべてのシェイプを含む配列を作成し、返します。
type: docs
weight: 326
url: /ja/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() メソッド


すべてのシェイプを含む配列を作成し、返します。

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### 戻り値

[IShape](../../ishape/) オブジェクトの配列。

## ShapeCollection::ToArray(int32_t, int32_t) メソッド


指定された範囲のすべてのシェイプを含む配列を作成し、返します。

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 返す最初のシェイプのインデックス。 |
| count | **int32_t** | 返すシェイプの数。 |

### 戻り値

[IShape](../../ishape/) オブジェクトの配列。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)