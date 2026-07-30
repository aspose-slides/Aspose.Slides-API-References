---
title: AddZoomFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 92
url: /it/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metodo

Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Il [ISlide](../../islide/) a cui fa riferimento il frame Zoom; deve appartenere a questa presentazione. |

### Valore restituito

Il [IZoomFrame](../../izoomframe/) appena creato.

## Osservazioni

Questo esempio dimostra come aggiungere un oggetto Zoom alla fine di una raccolta (supponendo che nella presentazione "Presentation.pptx" ci siano almeno due diapositive): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metodo

Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Il [ISlide](../../islide/) a cui fa riferimento il frame Zoom; deve appartenere a questa presentazione. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L'immagine per la diapositiva referenziata [IPPImage](../../ippimage/). |

### Valore restituito

Il [IZoomFrame](../../izoomframe/) appena creato.

## Osservazioni

Questo esempio dimostra come aggiungere un oggetto Zoom alla fine di una raccolta (supponendo che nella presentazione "Presentation.pptx" ci siano almeno due diapositive): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IZoomFrame](../../izoomframe/)
* Classe [ISlide](../../islide/)
* Classe [IShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)