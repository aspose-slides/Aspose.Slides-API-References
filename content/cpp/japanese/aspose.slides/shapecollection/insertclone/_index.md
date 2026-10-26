---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。
type: docs
weight: 560
url: /ja/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローンする[IShape](../../ishape/)。 |
| x | **float** | クローンされた形状\\u2019のフレームの x 座標（ポイント単位）。 |
| y | **float** | クローンされた形状\\u2019のフレームの y 座標（ポイント単位）。 |
| width | **float** | クローンされた形状\\u2019のフレームの幅（ポイント単位）。 |
| height | **float** | クローンされた形状\\u2019のフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された[IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。新しいシェイプは *sourceShape* の幅と高さを保持します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローンする[IShape](../../ishape/)。 |
| x | **float** | クローンされた形状\\u2019のフレームの x 座標（ポイント単位）。 |
| y | **float** | クローンされた形状\\u2019のフレームの y 座標（ポイント単位）。 |

### 戻り値

新しく作成された[IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。クローンされたシェイプは元の\\u2019の位置とサイズを保持します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローンする[IShape](../../ishape/)。 |

### 戻り値

新しく作成された[IShape](../../ishape/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)