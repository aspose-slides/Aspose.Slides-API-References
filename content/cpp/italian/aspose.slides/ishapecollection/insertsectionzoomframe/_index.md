---
title: InsertSectionZoomFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame Section Zoom e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 131
url: /it/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metodo


Crea un nuovo frame Zoom [Section](../../section/) e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame Zoom [Section](../../section/). |
| x | **float** | La coordinata x del nuovo frame Zoom [Section](../../section/), in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom [Section](../../section/), in punti. |
| width | **float** | La larghezza del nuovo frame Zoom [Section](../../section/), in punti. |
| height | **float** | L'altezza del nuovo frame Zoom [Section](../../section/), in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) a cui fa riferimento il frame Zoom [Section](../../section/); deve appartenere a questa presentazione e contenere almeno una diapositiva. |

### Valore restituito

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Note


Questo esempio dimostra la creazione e l'inserimento di un oggetto Zoom [Section](../../section/) all'indice specificato di una collezione (supponendo che nella presentazione "Presentation.pptx" ci siano almeno due sezioni): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metodo


Crea un nuovo frame Zoom [Section](../../section/) con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame Zoom [Section](../../section/). |
| x | **float** | La coordinata x del nuovo frame Zoom [Section](../../section/), in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom [Section](../../section/), in punti. |
| width | **float** | La larghezza del nuovo frame Zoom [Section](../../section/), in punti. |
| height | **float** | L'altezza del nuovo frame Zoom [Section](../../section/), in punti. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Il [ISection](../../isection/) a cui fa riferimento il frame Zoom [Section](../../section/); deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L'immagine da visualizzare all'interno del frame Zoom [Section](../../section/). |

### Valore restituito

Il [ISectionZoomFrame](../../isectionzoomframe/) appena creato.

## Note


Questo esempio dimostra la creazione e l'inserimento di un oggetto Zoom [Section](../../section/) all'indice specificato di una collezione (supponendo che nella presentazione "Presentation.pptx" ci siano almeno due sezioni): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)