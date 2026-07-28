---
title: get_IsWriteProtected()
second_title: Aspose.Slides C++ API referenciája
description: Lekér egy értéket, amely azt jelzi, hogy a csatolt prezentáció írásvédett-e.
type: docs
weight: 27
url: /hu/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metódus


Egy értéket kap, amely azt jelzi, hogy a csatolt prezentáció írásvédett-e.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Megjegyzés



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Ha a prezentációt jelszóval védik a megnyitáshoz, akkor a tulajdonság értéke egyenlő a NotDefined értékkel. 
## Lásd még

* Enum [NullableBool](../../nullablebool/)
* Osztály [PresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)