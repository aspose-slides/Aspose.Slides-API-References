---
title: get_ParentShape()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a forma pai ou nulo se o objeto pai não implementar a interface IShape somente leitura IShape.
type: docs
weight: 66
url: /pt/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() método


Retorna a forma pai ou nulo se o objeto pai não implementar a interface [IShape](../../ishape/) somente leitura [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Observações


O exemplo de código a seguir mostra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)