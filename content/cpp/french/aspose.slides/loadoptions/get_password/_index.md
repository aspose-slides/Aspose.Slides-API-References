---
title: get_Password()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient le mot de passe. Lire System::String."
type: docs
weight: 105
url: /fr/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() méthode


Obtient le mot de passe. Lire [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Remarques


Le mot de passe. 

Le code d'exemple suivant montre comment ouvrir un PowerPoint protégé par mot de passe [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// travailler avec la présentation déchiffrée
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)