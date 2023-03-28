---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API Reference
description: Gets a value that indicates whether a binded presentation is protected by a password to open.
type: docs
weight: 14
url: /cpp/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() method


Gets a value that indicates whether a binded presentation is protected by a password to open.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Remarks



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## See Also

* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
