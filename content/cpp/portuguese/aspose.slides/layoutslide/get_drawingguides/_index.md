---
title: get_DrawingGuides()
second_title: Aspose.Slides para C++ - Referência da API
description: Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura IDrawingGuidesCollection
type: docs
weight: 118
url: /pt/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() método


Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Adicionando o novo guia de desenho vertical à esquerda do centro do slide
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ver também

* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [LayoutSlide](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)