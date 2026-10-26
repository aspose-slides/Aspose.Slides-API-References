---
title: get_DrawingGuides()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura IDrawingGuidesCollection
type: docs
weight: 79
url: /pt/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() método

Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [ILayoutSlide](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)