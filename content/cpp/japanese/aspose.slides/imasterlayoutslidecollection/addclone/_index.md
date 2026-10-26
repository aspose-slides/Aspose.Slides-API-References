---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。
type: docs
weight: 1
url: /ja/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) メソッド

指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |

### 戻り値

追加されたスライド。

## 備考

1) 新しいレイアウトはこのレイアウトスライドコレクションの親マスタースライドとリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けに相当します。 2) このメソッドに相当するものは、[IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) メソッドで、[IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) プロパティからアクセスできます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)