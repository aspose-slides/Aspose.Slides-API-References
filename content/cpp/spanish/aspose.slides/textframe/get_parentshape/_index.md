---
title: get_ParentShape()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape de solo lectura IShape.
type: docs
weight: 92
url: /es/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() método

Devuelve la forma padre o null si el objeto padre no implementa la interfaz [IShape](../../ishape/) de solo lectura [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
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
* Clase [TextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)