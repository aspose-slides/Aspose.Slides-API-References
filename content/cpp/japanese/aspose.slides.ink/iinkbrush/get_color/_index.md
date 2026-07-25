---
title: get_Color()
second_title: Aspose.Slides for C++ API リファレンス
description: ラインのブラシの色を取得します。
type: docs
weight: 1
url: /ja/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() メソッド


ラインのブラシの色を取得します。

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
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

## 参照

* クラス [Color](../../../system.drawing/color/)
* クラス [IInkBrush](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)