---
title: InsertSectionZoomFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame Section Zoom e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 144
url: /it/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metodo


Crea un nuovo [Section](../../section/) Zoom frame e lo inserisce nella collezione di forme all'indice specificato.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il [Section](../../section/) Zoom frame. |
| x | **float** | La coordinata x del nuovo [Section](../../section/) Zoom frame, in punti. |
| y | **float** | La coordinata y del nuovo [Section](../../section/) Zoom frame, in punti. |
| width | **float** | La larghezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| height | **float** | L'altezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) a cui fa riferimento il [Section](../../section/) Zoom frame; deve appartenere a questa presentazione e contenere almeno una diapositiva. |

### Valore di ritorno

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Osservazioni


Questo esempio dimostra la creazione e l'inserimento di un oggetto [Section](../../section/) Zoom all'indice specificato di una collezione (si assume che ci siano almeno due sezioni nella presentazione "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metodo


Crea un nuovo [Section](../../section/) Zoom frame con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il [Section](../../section/) Zoom frame. |
| x | **float** | La coordinata x del nuovo [Section](../../section/) Zoom frame, in punti. |
| y | **float** | La coordinata y del nuovo [Section](../../section/) Zoom frame, in punti. |
| width | **float** | La larghezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| height | **float** | L'altezza del nuovo [Section](../../section/) Zoom frame, in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) a cui fa riferimento il [Section](../../section/) Zoom frame; deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L'immagine da visualizzare all'interno del [Section](../../section/) Zoom frame. |

### Valore di ritorno

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Osservazioni


Questo esempio dimostra la creazione e l'inserimento di un oggetto [Section](../../section/) Zoom all'indice specificato di una collezione (si assume che ci siano almeno due sezioni nella presentazione "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Vedi anche

* Definizione di tipo [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionZoomFrame](../../isectionzoomframe/)
* Classe [ISection](../../isection/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)