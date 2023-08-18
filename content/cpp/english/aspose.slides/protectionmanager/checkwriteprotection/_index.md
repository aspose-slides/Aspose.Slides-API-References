---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether a presentation is a password protected to modify.
type: docs
weight: 157
url: /aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) method


Determines whether a presentation is a password protected to modify.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
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



1. You should check the [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) property before calling this method.
1. When the password is null or empty, this method returns false.


## See Also

* Class [String](../../../system/string/)
* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)