---
title: Reorder()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたシェイプをシェイプコレクション内の新しい位置に移動します。
type: docs
weight: 300
url: /ja/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) メソッド

指定されたシェイプをシェイプコレクション内の新しい位置に移動します。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | シェイプが配置されるゼロベースの対象インデックス。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | コレクション内で移動する [IShape](../../ishape/)。 |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) メソッド

指定されたシェイプをシェイプコレクション内で移動し、指定されたインデックスから配置します。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 最初に指定されたシェイプが配置されるゼロベースの対象インデックス。続くシェイプは提供された順序で配置されます。 |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | コレクション内で移動する 1 つ以上の [IShape](../../ishape/) インスタンス。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IShape](../../ishape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)