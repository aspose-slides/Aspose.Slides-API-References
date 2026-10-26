---
title: get_Brush()
second_title: Aspose.Slides C++ API リファレンス
description: IInkLine の Brush を取得します（IInkBrush）。読み取り専用。
type: docs
weight: 1
url: /ja/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() メソッド

IInkLine [IInkBrush](../../iinkbrush/) の Brush を取得します。読み取り専用。

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IInkBrush](../../iinkbrush/)
* クラス [IInkTrace](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)