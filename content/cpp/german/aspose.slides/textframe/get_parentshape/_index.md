---
title: get_ParentShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das übergeordnete Shape zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur Lesezugriff IShape.
type: docs
weight: 92
url: /de/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() method


Gibt das übergeordnete Shape zurück oder null, wenn das übergeordnete Objekt das [IShape](../../ishape/) Interface nicht implementiert. Nur Lesezugriff [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
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
* Klasse [TextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)