---
title: get_ParentShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape en lecture seule IShape.
type: docs
weight: 92
url: /fr/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() méthode

Renvoie la forme parente ou null si l’objet parent n’implémente pas l’interface [IShape](../../ishape/) en lecture seule [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Remarques

L’exemple de code suivant montre
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [TextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)