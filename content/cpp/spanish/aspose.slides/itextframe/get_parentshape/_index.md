---
title: get_ParentShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la forma principal o null si el objeto principal no implementa la interfaz IShape de solo lectura IShape.
type: docs
weight: 66
url: /es/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() método


Devuelve la forma principal o null si el objeto principal no implementa la interfaz [IShape](../../ishape/) de solo lectura [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Observaciones


El siguiente ejemplo de código muestra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../ishape/)
* Clase [ITextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)