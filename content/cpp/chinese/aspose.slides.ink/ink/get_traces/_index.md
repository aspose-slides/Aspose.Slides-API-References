---
title: get_Traces()
second_title: Aspose.Slides for C++ API 参考
description: 获取 IInk 元素 IInkTrace 中的所有跟踪。只读。
type: docs
weight: 1
url: /zh/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() 方法


获取 [IInk](../../iink/) 元素 [IInkTrace](../../iinktrace/) 中的所有跟踪。只读。

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IInkTrace](../../iinktrace/)
* 类 [Ink](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)