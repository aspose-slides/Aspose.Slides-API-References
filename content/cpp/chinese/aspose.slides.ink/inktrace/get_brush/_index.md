---
title: get_Brush()
second_title: Aspose.Slides C++ API 参考
description: 获取 IInkLine IInkBrush 的 Brush，只读。
type: docs
weight: 1
url: /zh/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() 方法


获取 IInkLine [IInkBrush](../../iinkbrush/) 的 Brush，只读。

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## 备注


示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IInkBrush](../../iinkbrush/)
* 类 [InkTrace](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)