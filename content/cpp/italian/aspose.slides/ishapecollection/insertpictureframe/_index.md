---
title: InsertPictureFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 417
url: /it/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metodo

Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame immagine. |
| shapeType | [ShapeType](../../shapetype/) | Specifica il tipo di forma contenuto in [ShapeType](../../shapetype/), eccetto tutti i tipi di linee:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | La coordinata x del frame immagine, in punti. |
| y | **float** | La coordinata y del frame immagine, in punti. |
| width | **float** | La larghezza del frame immagine, in punti. |
| height | **float** | L'altezza del frame immagine, in punti. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Il [IPPImage](../../ippimage/) da visualizzare nel frame immagine. |

### Valore restituito

Il [IPictureFrame](../../ipictureframe/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPictureFrame](../../ipictureframe/)
* Classe [IPPImage](../../ippimage/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)