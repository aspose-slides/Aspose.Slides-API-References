---
title: get_Size()
second_title: Aspose.Slides for C++ API リファレンス
description: 線のブラシサイズをポイント単位で取得します。
type: docs
weight: 27
url: /ja/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() メソッド


線のブラシサイズをポイント単位で取得します。

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## 参照

* クラス [SizeF](../../../system.drawing/sizef/)
* クラス [InkBrush](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)