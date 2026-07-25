---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドの描画ガイドのコレクションを返します。読み取り専用 IDrawingGuidesCollection
type: docs
weight: 79
url: /ja/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() メソッド

レイアウトスライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## 備考

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// スライドの中心の左側に新しい垂直描画ガイドを追加します
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDrawingGuidesCollection](../../idrawingguidescollection/)
* クラス [ILayoutSlide](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)