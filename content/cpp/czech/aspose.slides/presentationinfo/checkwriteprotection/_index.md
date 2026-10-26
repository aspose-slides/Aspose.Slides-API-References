---
title: CheckWriteProtection()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Kontroluje, zda je heslo pro úpravu správné u prezentace chráněné proti zápisu.
type: docs
weight: 66
url: /cs/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metoda


Checks whether a password to modify is correct for a write protected presentation.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo k ověření. |

### Návratová hodnota

True pokud je prezentace chráněna proti zápisu a heslo je správné. False jinak.
## Poznámky



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Měli byste zkontrolovat vlastnost [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) před voláním této metody.
1. Když je heslo null nebo prázdné, tato metoda vrací false.



## Viz také

* Třída [String](../../../system/string/)
* Třída [PresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)