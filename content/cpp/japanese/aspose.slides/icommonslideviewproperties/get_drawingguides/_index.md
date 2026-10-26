---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API リファレンス
description: 描画ガイドのコレクションを返します。読み取り専用 IDrawingGuidesCollection
type: docs
weight: 53
url: /ja/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() メソッド


描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## 備考


次のサンプルコードは、PowerPoint プレゼンテーションに新しい描画ガイドを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// スライドの中心の右側に新しい垂直描画ガイドを追加します
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// スライドの中心の下に新しい水平描画ガイドを追加します
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDrawingGuidesCollection](../../idrawingguidescollection/)
* クラス [ICommonSlideViewProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)