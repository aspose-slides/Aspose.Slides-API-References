---
title: get_Traces()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 IInk 元素 IInkTrace 中的所有痕跡。唯讀。
type: docs
weight: 1
url: /zh-hant/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() 方法


取得所有位於 [IInk](../) 元素 [IInkTrace](../../iinktrace/) 中的痕跡。唯讀。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IInkTrace](../../iinktrace/)
* 類別 [IInk](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)