---
title: get_ParentShape()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Zwraca kształt nadrzędny lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape. Tylko do odczytu IShape.
type: docs
weight: 92
url: /pl/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metoda


Zwraca kształt nadrzędny lub null, jeśli obiekt nadrzędny nie implementuje interfejsu [IShape](../../ishape/) Tylko do odczytu [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Uwagi


Poniższy przykład kodu pokazuje 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [TextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)