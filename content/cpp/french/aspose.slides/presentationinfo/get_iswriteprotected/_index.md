---
title: get_IsWriteProtected()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une valeur qui indique si une présentation liée est protégée en écriture.
type: docs
weight: 27
url: /fr/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() méthode

Obtient une valeur qui indique si une présentation liée est protégée en écriture.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Remarques



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Si la présentation est protégée par un mot de passe à l'ouverture, la valeur de la propriété est égale à NotDefined. 
## Voir aussi

* Énum [NullableBool](../../nullablebool/)
* Classe [PresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)