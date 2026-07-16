---
title: get_IsPasswordProtected()
second_title: Référence de l'API Aspose.Slides pour C++
description: Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule bool.
type: docs
weight: 40
url: /fr/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() méthode


Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Voir aussi

* Classe [VbaProject](../)
* Espace de noms [Aspose::Slides::Vba](../../)
* Bibliothèque [Aspose.Slides](../../../)