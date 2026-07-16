---
title: set_Password()
second_title: Référence API Aspose.Slides pour C++
description: "Définit le mot de passe. Écrivez System::String."
type: docs
weight: 118
url: /fr/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) méthode


Définit le mot de passe. Écrivez [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Remarques


Le mot de passe. 

Le code d'exemple suivant montre comment ouvrir un PowerPoint protégé par mot de passe [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)