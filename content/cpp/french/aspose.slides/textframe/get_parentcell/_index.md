---
title: get_ParentCell()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface ICell. Lecture seule ICell.
type: docs
weight: 105
url: /fr/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() méthode

Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface [ICell](../../icell/). Lecture seule [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Remarques

L'exemple de code suivant montre
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICell](../../icell/)
* Classe [TextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)