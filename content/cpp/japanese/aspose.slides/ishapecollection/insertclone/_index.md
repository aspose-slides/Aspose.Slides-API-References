---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。
type: docs
weight: 508
url: /ja/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) メソッド


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象となる[IShape](../../ishape/)。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（単位はポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（単位はポイント）。 |
| width | **float** | クローンされたシェイプのフレームの幅（単位はポイント）。 |
| height | **float** | クローンされたシェイプのフレームの高さ（単位はポイント）。 |

### Return Value

新しく作成された[IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) メソッド


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。新しいシェイプは *sourceShape* の幅と高さを保持します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象となる[IShape](../../ishape/)。 |
| x | **float** | クローンされたシェイプのフレームの x 座標（単位はポイント）。 |
| y | **float** | クローンされたシェイプのフレームの y 座標（単位はポイント）。 |

### Return Value

新しく作成された[IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) メソッド


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象となる[IShape](../../ishape/)。 |

### Return Value

新しく作成された[IShape](../../ishape/)。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)