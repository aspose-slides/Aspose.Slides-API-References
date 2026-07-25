---
title: ToArray()
second_title: Aspose.Slides for C++ API リファレンス
description: すべてのシェイプを含む配列を作成して返します。
type: docs
weight: 287
url: /ja/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() メソッド

すべてのシェイプを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### 戻り値

[IShape](../../ishape/) オブジェクトの配列です。

## IShapeCollection::ToArray(int32_t, int32_t) メソッド

指定された範囲内のすべてのシェイプを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 返す最初のシェイプのインデックスです。 |
| count | **int32_t** | 返すシェイプの数です。 |

### 戻り値

[IShape](../../ishape/) オブジェクトの配列です。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)