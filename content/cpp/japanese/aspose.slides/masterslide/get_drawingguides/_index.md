---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API リファレンス
description: マスタースライドの描画ガイドのコレクションを返します。読み取り専用 IDrawingGuidesCollection
type: docs
weight: 170
url: /ja/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() メソッド


マスタースライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// スライド中心の右側に新しい垂直描画ガイドを追加します
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDrawingGuidesCollection](../../idrawingguidescollection/)
* クラス [MasterSlide](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)