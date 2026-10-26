---
title: License()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de cette classe.
type: docs
weight: 1
url: /fr/aspose.slides/license/license/
---
## Constructeur License::License()


Initialise une nouvelle instance de cette classe.

```cpp
Aspose::Slides::License::License()
```

## Remarques


Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier qui contient le composant, dans le dossier qui contient l'assembly appelant, dans le dossier de l'assembly d'entrée et enfin dans les ressources incorporées de l'assembly appelant. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Voir aussi

* Classe [License](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)