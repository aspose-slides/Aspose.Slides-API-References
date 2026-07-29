---
title: CheckWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om en presentation är lösenordsskyddad för att modifieras.
type: docs
weight: 157
url: /sv/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metod


Avgör om en presentation är lösenordsskyddad för att modifieras.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet för kontroll. |

### Returvärde

True om lösenordet är giltigt; annars false.
## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Du bör kontrollera [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) egenskapen innan du anropar denna metod.
1. När lösenordet är null eller tomt, returnerar denna metod false.


## Se även

* Klass [String](../../../system/string/)
* Klass [ProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)