---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 547
url: /ja/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象のシェイプ。 |
| x | **float** | 新しいシェイプのフレームの X 座標（ポイント）。 |
| y | **float** | 新しいシェイプのフレームの Y 座標（ポイント）。 |
| width | **float** | 新しいシェイプのフレームの幅（ポイント）。 |
| height | **float** | 新しいシェイプのフレームの高さ（ポイント）。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。新しいシェイプは *sourceShape* の幅と高さを保持します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象のシェイプ。 |
| x | **float** | 新しいシェイプのフレームの X 座標（ポイント）。 |
| y | **float** | 新しいシェイプのフレームの Y 座標（ポイント）。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象の [IShape](../../ishape/)。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)