---
title: CheckPassword()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een wachtwoord correct is voor een presentatie die is beveiligd met een open wachtwoord.
type: docs
weight: 53
url: /nl/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) methode


Controleert of een wachtwoord correct is voor een presentatie die is beveiligd met een open wachtwoord.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord om te controleren. |

### Retourwaarde

True als de presentatie is beveiligd met een open wachtwoord en het wachtwoord correct is, en false anders.
## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Wanneer het wachtwoord null of leeg is, geeft deze methode false terug. 
## Zie ook

* Class [String](../../../system/string/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)