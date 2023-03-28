---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether a presentation is a password protected to modify.
type: docs
weight: 157
url: /cpp/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection([System::String](../../../system/string/)) method


Determines whether a presentation is a password protected to modify.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | The password for checking. |

### Return Value

True if the password is valid; otherwise, false.
## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. You should check the [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) property before calling this method.
1. When the password is null or empty, this method returns false.


## See Also

* Class [String](../../../system/string/)
* Class [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
