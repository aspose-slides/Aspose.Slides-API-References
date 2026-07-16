---
title: get_IsPasswordProtected()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si une présentation liée est protégée par un mot de passe à l'ouverture.
type: docs
weight: 14
url: /fr/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() méthode


Obtient une valeur qui indique si une présentation liée est protégée par un mot de passe à l'ouverture.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Remarques



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Voir aussi

* Classe [IPresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)