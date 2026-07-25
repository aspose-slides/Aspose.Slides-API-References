---
title: get_Points()
second_title: Aspose.Slides for C++ API リファレンス
description: "IInkLine System::Drawing::PointF のポイントを取得します。読み取り専用です。"
type: docs
weight: 14
url: /ja/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() method

IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) のポイントを取得します。読み取り専用です。

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IInkTrace](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)