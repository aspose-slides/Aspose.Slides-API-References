---
title: get_IsWriteProtected()
second_title: Aspose.Slides pro C++ – referenční příručka
description: Vrací hodnotu, která určuje, zda je svázaná prezentace chráněna proti zápisu.
type: docs
weight: 27
url: /cs/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() metoda


Vrací hodnotu, která určuje, zda je svázaná prezentace chráněna proti zápisu.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Poznámky



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Pokud je prezentace chráněna heslem pro otevření, hodnota vlastnosti je rovna NotDefined. Viz výčtový typ [NullableBool](../../nullablebool/). 
## Viz také

* Enum [NullableBool](../../nullablebool/)
* Třída [IPresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)