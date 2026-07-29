---
title: CheckWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om en presentation är lösenordsskyddad för att modifieras.
type: docs
weight: 157
url: /sv/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metod

Avgör om en presentation är lösenordsskyddad för att modifieras.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet för kontroll. |

### Returvärde

Sant om lösenordet är giltigt; annars falskt.

## Anmärkningar

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Du bör kontrollera egenskapen [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) innan du anropar den här metoden.
1. När lösenordet är null eller tomt, returnerar den här metoden falskt.

## Se även

* Klass [String](../../../system/string/)
* Klass [IProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)