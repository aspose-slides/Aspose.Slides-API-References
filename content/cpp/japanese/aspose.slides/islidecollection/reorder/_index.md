---
title: Reorder()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内のスライドを指定された位置に移動します。
type: docs
weight: 105
url: /ja/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) メソッド


スライドをコレクションから指定した位置に移動します。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 対象インデックス。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) を移動します。 |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) メソッド


スライドをコレクションから指定した位置に移動します。[Slides](../../) はインデックスからリストに表示される順序で配置されます。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 対象インデックス。 |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) を移動します。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ISlide](../../islide/)
* クラス [ISlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)