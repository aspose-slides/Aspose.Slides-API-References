---
title: AddPictureFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova cornice immagine contenente l'immagine specificata e la aggiunge alla fine della collezione di forme.
type: docs
weight: 404
url: /it/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metodo

Crea una nuova cornice immagine contenente l’immagine specificata e la aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Specifica il tipo di forma contenuto in [ShapeType](../../shapetype/), ad eccezione di tutti i tipi di linee:<br>[ShapeType::Line](../../shapetype/),<br>[ShapeType::StraightConnector1](../../shapetype/),<br>[ShapeType::BentConnector2](../../shapetype/),<br>[ShapeType::BentConnector3](../../shapetype/),<br>[ShapeType::BentConnector4](../../shapetype/),<br>[ShapeType::BentConnector5](../../shapetype/),<br>[ShapeType::CurvedConnector2](../../shapetype/),<br>[ShapeType::CurvedConnector3](../../shapetype/),<br>[ShapeType::CurvedConnector4](../../shapetype/),<br>[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | La coordinata x della cornice immagine, in punti. |
| y | **float** | La coordinata y della cornice immagine, in punti. |
| width | **float** | La larghezza della cornice immagine, in punti. |
| height | **float** | L’altezza della cornice immagine, in punti. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Il [IPPImage](../../ippimage/) da visualizzare nella cornice dell’immagine. |

### Valore di ritorno

Il [IPictureFrame](../../ipictureframe/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)