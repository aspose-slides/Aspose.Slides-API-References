---
title: get_IsPasswordProtected()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une valeur indiquant si une présentation liée est protégée par un mot de passe à l'ouverture.
type: docs
weight: 14
url: /fr/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() méthode


Obtient une valeur qui indique si une présentation liée est protégée par un mot de passe à l'ouverture.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Remarques



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Voir aussi

* Classe [PresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)