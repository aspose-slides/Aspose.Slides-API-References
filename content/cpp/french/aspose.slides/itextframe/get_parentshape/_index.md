---
title: get_ParentShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape Lecture seule IShape.
type: docs
weight: 66
url: /fr/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() méthode


Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface [IShape](../../ishape/) Lecture seule [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Remarques


L'exemple de code suivant montre 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ITextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)