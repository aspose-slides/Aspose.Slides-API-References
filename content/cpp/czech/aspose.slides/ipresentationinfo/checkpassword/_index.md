---
title: CheckPassword()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda je heslo správné pro prezentaci chráněnou otevřeným heslem.
type: docs
weight: 53
url: /cs/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) metoda

Kontroluje, zda je heslo správné pro prezentaci chráněnou otevřeným heslem.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo k ověření. |

### Návratová hodnota

True, pokud je prezentace chráněna otevřeným heslem a heslo je správné, a false v opačném případě.

## Poznámky

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Když je heslo null nebo prázdné, tato metoda vrací false.

## Viz také

* Třída [String](../../../system/string/)
* Třída [IPresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)