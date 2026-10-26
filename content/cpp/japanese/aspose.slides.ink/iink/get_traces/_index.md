---
title: get_Traces()
second_title: Aspose.Slides for C++ API リファレンス
description: IInk 要素 IInkTrace に含まれるすべてのトレースを取得します。読み取り専用です。
type: docs
weight: 1
url: /ja/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() メソッド


[IInk](../) 要素 [IInkTrace](../../iinktrace/) に含まれるすべてのトレースを取得します。読み取り専用です。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IInkTrace](../../iinktrace/)
* クラス [IInk](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* ライブラリ [Aspose.Slides](../../../)