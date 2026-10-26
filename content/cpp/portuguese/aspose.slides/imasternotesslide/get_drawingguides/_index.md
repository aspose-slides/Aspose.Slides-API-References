---
title: get_DrawingGuides()
second_title: Referência de API do Aspose.Slides para C++
description: Retorna uma coleção de guias de desenho para o slide mestre de notas. Somente leitura IDrawingGuidesCollection
type: docs
weight: 27
url: /pt/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() método

Retorna uma coleção de guias de desenho para o slide mestre de notas. Somente leitura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
```

## Observações

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adicionando o novo guia de desenho horizontal abaixo do centro do slide
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [IMasterNotesSlide](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)