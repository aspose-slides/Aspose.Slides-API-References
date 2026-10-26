---
title: get_LinkPathRelative()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule System::String."
type: docs
weight: 118
url: /fr/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() méthode

Renvoie le chemin relatif d'un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
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
* Classe [IOleObjectFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)