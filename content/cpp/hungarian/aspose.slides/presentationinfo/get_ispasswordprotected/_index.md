---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy értéket, amely azt jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz.
type: docs
weight: 14
url: /hu/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metódus

Visszaad egy értéket, amely azt jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Megjegyzések

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Lásd még

* Osztály [PresentationInfo](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)