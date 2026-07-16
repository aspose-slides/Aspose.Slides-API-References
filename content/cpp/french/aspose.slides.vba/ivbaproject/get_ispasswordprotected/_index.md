---
title: get_IsPasswordProtected()
second_title: Référence API Aspose.Slides pour C++
description: Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule bool.
type: docs
weight: 40
url: /fr/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() méthode


Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Classe [IVbaProject](../)
* Espace de noms [Aspose::Slides::Vba](../../)
* Bibliothèque [Aspose.Slides](../../../)