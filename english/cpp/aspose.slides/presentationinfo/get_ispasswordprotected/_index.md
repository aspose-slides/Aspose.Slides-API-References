---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API Reference
description: Gets a value that indicates whether a binded presentation is protected by a password to open.
type: docs
weight: 14
url: /cpp/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() method


Gets a value that indicates whether a binded presentation is protected by a password to open.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Remarks



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## See Also

* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)