---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ Referência da API
description: Retorna uma coleção de guias de desenho para o slide mestre de folheto. Somente leitura IDrawingGuidesCollection
type: docs
weight: 53
url: /pt/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() método


Retorna uma coleção de guias de desenho para o slide mestre de folheto. Somente leitura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adicionando o novo guia de desenho horizontal acima do centro do slide
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* classe [MasterHandoutSlide](../)
* espaço de nomes [Aspose::Slides](../../)
* biblioteca [Aspose.Slides](../../../)