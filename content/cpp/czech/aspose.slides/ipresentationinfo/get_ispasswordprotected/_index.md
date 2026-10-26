---
title: get_IsPasswordProtected()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu, která určuje, zda je svázaná prezentace chráněna heslem pro otevření.
type: docs
weight: 14
url: /cs/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metoda

Vrací hodnotu, která udává, zda je svázaná prezentace chráněna heslem pro otevření.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Poznámky



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Viz také

* Třída [IPresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)