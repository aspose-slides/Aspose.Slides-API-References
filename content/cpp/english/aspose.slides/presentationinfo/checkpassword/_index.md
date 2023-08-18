---
title: CheckPassword()
second_title: Aspose.Slides for C++ API Reference
description: Checks whether a password is correct for a presentation protected with open password.
type: docs
weight: 53
url: /aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) method


Checks whether a password is correct for a presentation protected with open password.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | The password to check. |

### Return Value

True if the presentation is protected with open password and the password is correct and false otherwise.
## Remarks



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



When the password is null or empty, this method returns false. 

## See Also

* Class [String](../../../system/string/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)