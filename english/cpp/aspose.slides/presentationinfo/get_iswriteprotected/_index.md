---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API Reference
description: Gets a value that indicates whether a binded presentation is write protected.
type: docs
weight: 27
url: /cpp/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() method


Gets a value that indicates whether a binded presentation is write protected.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Remarks



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == Aspose::Slides::NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


If the presentation is protected by a password to open, the property value equals NotDefined. 
## See Also

* Enum [NullableBool](../../nullablebool/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
