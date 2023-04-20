---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Reference
description: Checks whether a password to modify is correct for a write protected presentation.
type: docs
weight: 66
url: /cpp/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) method


Checks whether a password to modify is correct for a write protected presentation.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | The password to check. |

### Return Value

True if the presentation is write protected and the password is correct. False otherwise.
## Remarks



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == Aspose::Slides::NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. You should check the [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) property before calling this method.
1. When password is null or empty, this method returns false.



## See Also

* Class [String](../../../system/string/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)