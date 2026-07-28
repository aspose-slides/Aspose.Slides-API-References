---
title: get_IsWriteProtected()
second_title: Aspose.Slides C++ API Referencia
description: Egy értéket ad vissza, amely azt jelzi, hogy a csatolt prezentáció írásvédett-e.
type: docs
weight: 27
url: /hu/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() metódus


Egy értéket ad vissza, amely azt jelzi, hogy a csatolt prezentáció írásvédett-e.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Megjegyzések



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Ha a prezentáció jelszóval védett a megnyitáshoz, akkor a tulajdonság értéke NotDefined. Lásd [NullableBool](../../nullablebool/) enumeráció. 
## Lásd még

* Enum [NullableBool](../../nullablebool/)
* Osztály [IPresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)