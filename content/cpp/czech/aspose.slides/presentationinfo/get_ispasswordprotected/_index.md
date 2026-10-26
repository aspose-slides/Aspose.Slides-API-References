---
title: get_IsPasswordProtected()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací hodnotu, která určuje, zda je svázaná prezentace chráněna heslem pro otevření.
type: docs
weight: 14
url: /cs/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metoda


Vrací hodnotu, která určuje, zda je svázaná prezentace chráněna heslem pro otevření.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Poznámky



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Viz také

* Třída [PresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)