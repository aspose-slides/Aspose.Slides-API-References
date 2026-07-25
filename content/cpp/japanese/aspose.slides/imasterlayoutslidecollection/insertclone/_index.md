---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウト スライドのコピーをコレクションの指定位置に挿入します。
type: docs
weight: 14
url: /ja/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) メソッド


指定されたレイアウト スライドのコピーをコレクションの指定位置に挿入します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンする。 |

### 戻り値

挿入されたスライド。

## 備考



新しいレイアウトは、このレイアウト スライド コレクションの親マスタースライドにリンクされます。したがって、PowerPoint の \"Use Destination Theme\" オプションを使用したコピー/ペーストと同等です。

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)