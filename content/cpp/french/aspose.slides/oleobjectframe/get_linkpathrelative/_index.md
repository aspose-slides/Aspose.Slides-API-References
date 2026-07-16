---
title: get_LinkPathRelative()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie le chemin relatif vers un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule System::String."
type: docs
weight: 131
url: /fr/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() méthode


Renvoie le chemin relatif vers un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Remarques


Dans les présentations Ppt, certains liens d'objets Ole peuvent avoir une représentation relative. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [OleObjectFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)