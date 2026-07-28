---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API referencia
description: Lekér egy értéket, amely jelzi, hogy a csatolt bemutató jelszóval védett-e a megnyitáskor.
type: docs
weight: 14
url: /hu/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metódus


Lekér egy értéket, amely jelzi, hogy a csatolt bemutató jelszóval védett-e a megnyitáskor.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Megjegyzések


```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Lásd még

* Osztály [IPresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)