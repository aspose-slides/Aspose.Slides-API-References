---
title: get_ParentShape()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca nadrzędny kształt lub null, jeśli obiekt nadrzędny nie implementuje interfejsu IShape typu tylko do odczytu IShape.
type: docs
weight: 66
url: /pl/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metoda

Zwraca nadrzędny kształt lub null, jeśli obiekt nadrzędny nie implementuje interfejsu [IShape](../../ishape/) typu tylko do odczytu [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Uwagi

Poniższy fragment kodu pokazuje 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [ITextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)