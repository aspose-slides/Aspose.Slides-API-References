---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションからレイアウトを削除します。
type: docs
weight: 27
url: /ja/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) メソッド


コレクションからレイアウトを削除します。

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | コレクションから削除するレイアウト スライドです。 |
## 備考

1) PptxEditException のスローを防ぐために、事前に layout の HasDependingSlides プロパティを確認してください。 2) コードを簡略化するために、[ILayoutSlide::Remove](../../ilayoutslide/remove/) メソッドも使用できます。 
## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [ILayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)