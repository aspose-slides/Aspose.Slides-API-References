---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API Reference
description: "Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly System::String."
type: docs
weight: 131
url: /cpp/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() method


Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Remarks


In the Ppt presentations, some Ole object links may have a relative representation. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## See Also

* Class [String](../../../system/string/)
* Class [OleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)