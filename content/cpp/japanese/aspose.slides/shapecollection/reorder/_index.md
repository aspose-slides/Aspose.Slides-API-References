---
title: Reorder()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定されたシェイプをシェイプコレクション内の新しい位置に移動します。
type: docs
weight: 339
url: /ja/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) メソッド

指定されたシェイプをシェイプコレクション内の新しい位置に移動します。

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | シェイプが配置されるゼロベースのターゲットインデックスです。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | コレクション内で移動させる [IShape](../../ishape/)。 |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) メソッド

指定されたシェイプをシェイプコレクション内で移動し、指定されたインデックスから配置します。

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 最初に指定されたシェイプが配置されるゼロベースのターゲットインデックスです。続くシェイプは提供された順序で配置されます。 |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | コレクション内で移動させる [IShape](../../ishape/) のインスタンスを1つ以上指定します。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IShape](../../ishape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)