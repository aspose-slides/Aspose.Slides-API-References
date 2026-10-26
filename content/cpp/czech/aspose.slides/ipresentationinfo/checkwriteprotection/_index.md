---
title: CheckWriteProtection()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda je heslo pro úpravu správné pro prezentaci chráněnou proti zápisu.
type: docs
weight: 66
url: /cs/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metoda


Kontroluje, zda je heslo pro úpravu správné pro prezentaci chráněnou proti zápisu.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo, které se má zkontrolovat. |

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



1. Měli byste zkontrolovat vlastnost [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) před voláním této metody.
1. Když je password null nebo prázdný, tato metoda vrací false.



## Viz také

* Třída [String](../../../system/string/)
* Třída [IPresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)