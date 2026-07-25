---
title: set_Color()
second_title: Aspose.Slides for C++ API リファレンス
description: 線のブラシ色を設定します。
type: docs
weight: 14
url: /ja/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) メソッド


線のブラシ色を設定します。

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## 関連項目

* クラス [Color](../../../system.drawing/color/)
* クラス [IInkBrush](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)