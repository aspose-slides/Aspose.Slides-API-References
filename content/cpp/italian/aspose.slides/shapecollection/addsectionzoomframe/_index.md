---
title: AddSectionZoomFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame Section Zoom e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 131
url: /it/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metodo

Crea un nuovo [Section](../../section/) Zoom frame e lo aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo [Section](../../section/) Zoom frame, in punti. |
| y | **float** | La coordinata y del nuovo [Section](../../section/) Zoom frame, in punti. |
| width | **float** | La larghezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| height | **float** | L'altezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) referenziato dal [Section](../../section/) Zoom frame; deve appartenere a questa presentazione e contenere almeno una diapositiva. |

### Valore di ritorno

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Osservazioni

Questo esempio dimostra come aggiungere un oggetto [Section](../../section/) Zoom alla fine di una collezione (supponendo che nella presentazione "Presentation.pptx" siano presenti almeno due sezioni): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metodo

Crea un nuovo [Section](../../section/) Zoom frame con un'immagine predefinita e lo aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo [Section](../../section/) Zoom frame, in punti. |
| y | **float** | La coordinata y del nuovo [Section](../../section/) Zoom frame, in punti. |
| width | **float** | La larghezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| height | **float** | L'altezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) referenziato dal [Section](../../section/) Zoom frame; deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Il [IPPImage](../../ippimage/) da visualizzare all'interno del [Section](../../section/) Zoom frame. |

### Valore di ritorno

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Osservazioni

Questo esempio dimostra come aggiungere un oggetto [Section](../../section/) Zoom alla fine di una collezione (supponendo che nella presentazione "Presentation.pptx" siano presenti almeno due sezioni): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)