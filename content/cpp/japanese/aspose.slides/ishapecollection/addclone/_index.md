---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 495
url: /ja/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) メソッド

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象のシェイプ。 |
| x | **float** | クローンされたシェイプ\\u2019s フレームの x 座標（ポイント単位）。 |
| y | **float** | クローンされたシェイプ\\u2019s フレームの y 座標（ポイント単位）。 |
| width | **float** | クローンされたシェイプ\\u2019s フレームの幅（ポイント単位）。 |
| height | **float** | クローンされたシェイプ\\u2019s フレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) メソッド

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。新しいシェイプは *sourceShape* の幅と高さを保持します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象の [IShape](../../ishape/)。 |
| x | **float** | クローンされたシェイプ\\u2019s フレームの x 座標（ポイント単位）。 |
| y | **float** | クローンされたシェイプ\\u2019s フレームの y 座標（ポイント単位）。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) メソッド

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。クローンされたシェイプは original\\u2019s 位置とサイズを保持します。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | クローン対象の [IShape](../../ishape/)。 |

### 戻り値

新しく作成された [IShape](../../ishape/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)