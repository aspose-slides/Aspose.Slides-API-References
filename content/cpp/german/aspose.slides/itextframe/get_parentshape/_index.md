---
title: get_ParentShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die übergeordnete Form zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur-Lesen IShape.
type: docs
weight: 66
url: /de/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() Methode


Gibt die übergeordnete Form zurück oder null, wenn das übergeordnete Objekt das [IShape](../../ishape/) Interface nicht implementiert. Nur-Lesen [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Hinweise


Das folgende Codebeispiel zeigt 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ITextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)