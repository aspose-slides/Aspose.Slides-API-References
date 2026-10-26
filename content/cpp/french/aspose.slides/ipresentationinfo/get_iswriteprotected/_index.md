---
title: get_IsWriteProtected()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur qui indique si une présentation liée est protégée en écriture.
type: docs
weight: 27
url: /fr/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() method


Renvoie une valeur qui indique si une présentation liée est protégée en écriture.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Remarques



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Si la présentation est protégée par un mot de passe à l'ouverture, la valeur de la propriété est égale à NotDefined. Voir l'énumération [NullableBool](../../nullablebool/). 
## Voir aussi

* Enum [NullableBool](../../nullablebool/)
* Classe [IPresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)