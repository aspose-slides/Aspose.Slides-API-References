---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウト スライドのコピーをコレクションの末尾に追加します。
type: docs
weight: 1
url: /ja/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) メソッド

Adds a copy of a specified layout slide to the end of the collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |

### 戻り値

追加されたスライド。

## 備考

1) 新しいレイアウトは、このレイアウト スライド コレクションの親マスタースライドにリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けと同等です。 2) このメソッドの類似は、[IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) メソッドで、[IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) プロパティからアクセスできます。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [MasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)