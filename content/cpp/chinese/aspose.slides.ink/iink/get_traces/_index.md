---
title: get_Traces()
second_title: Aspose.Slides C++ API 参考
description: 获取 IInk 元素 IInkTrace 中包含的所有跟踪。只读。
type: docs
weight: 1
url: /zh/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() 方法


获取所有包含在 [IInk](../) 元素 [IInkTrace](../../iinktrace/) 中的跟踪。只读。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkTrace](../../iinktrace/)
* Class [IInk](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)