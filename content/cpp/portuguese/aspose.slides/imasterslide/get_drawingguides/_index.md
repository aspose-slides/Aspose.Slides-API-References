---
title: get_DrawingGuides()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção de guias de desenho para o slide mestre. Somente leitura IDrawingGuidesCollection
type: docs
weight: 105
url: /pt/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() método


Retorna uma coleção de guias de desenho para o slide mestre. Somente leitura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Adicionando a nova guia de desenho vertical à direita do centro do slide
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [IMasterSlide](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)