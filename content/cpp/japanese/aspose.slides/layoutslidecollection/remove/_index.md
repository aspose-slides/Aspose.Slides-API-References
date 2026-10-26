---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションからレイアウトを削除します。
type: docs
weight: 66
url: /ja/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) メソッド

コレクションからレイアウトを削除します。

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | コレクションから削除するレイアウトスライドです。 |

## 備考

1) PptxEditException のスローを防ぐために、事前に layout の HasDependingSlides プロパティを確認してください。  
2) コードを簡素化するために、[ILayoutSlide::Remove](../../ilayoutslide/remove/) メソッドも使用できます。 

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [LayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)