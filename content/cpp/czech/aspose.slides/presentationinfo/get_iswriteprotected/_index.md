---
title: get_IsWriteProtected()
second_title: Aspose.Slides pro C++ API Reference
description: Získá hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu.
type: docs
weight: 27
url: /cs/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metoda

Získá hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Poznámky



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Pokud je prezentace chráněna heslem pro otevření, hodnota vlastnosti se rovná NotDefined. 
## Viz také

* Výčet [NullableBool](../../nullablebool/)
* Třída [PresentationInfo](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)