---
title: get_Traces()
second_title: Aspose.Slides for C++ API Reference
description: Gets all traces containing in the IInk element IInkTrace. Read-only.
type: docs
weight: 1
url: /aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() method


Gets all traces containing in the [IInk](../../iink/) element [IInkTrace](../../iinktrace/). Read-only.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkTrace](../../iinktrace/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)