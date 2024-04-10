---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API Reference
description: Indicates whether the VBAProject is protected by a password to view project properties. Read-only bool.
type: docs
weight: 40
url: /aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() method


Indicates whether the VBAProject is protected by a password to view project properties. Read-only **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## See Also

* Class [VbaProject](../)
* Namespace [Aspose::Slides::Vba](../../)
* Library [Aspose.Slides](../../../)