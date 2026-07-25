---
title: get_Points()
second_title: Aspose.Slides for C++ API リファレンス
description: "IInkLine の System::Drawing::PointF のポイントを取得します（読み取り専用）。"
type: docs
weight: 14
url: /ja/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() メソッド


IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) のポイントを取得します（読み取り専用）。

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [InkTrace](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)