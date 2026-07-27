---
title: get_ParentShape()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a forma pai ou nulo se o objeto pai não implementar a interface IShape Somente leitura IShape.
type: docs
weight: 92
url: /pt/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() método

Retorna a forma pai ou nulo se o objeto pai não implementar a interface [IShape](../../ishape/) Somente leitura [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Observações

O exemplo de código abaixo mostra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)