---
title: AddGroupShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma di gruppo vuota e la aggiunge alla fine della collezione di forme. Il frame del group\u2019s si adatterà automaticamente per contenere tutte le forme aggiunte.
type: docs
weight: 352
url: /it/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metodo

Crea una nuova forma di gruppo vuota e la aggiunge alla fine della collezione di forme. Il frame del group\\u2019s si adatterà automaticamente per contenere tutte le forme aggiunte.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Valore di ritorno

Il nuovo [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metodo

Crea una nuova forma di gruppo, converte l’immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Il [ISvgImage](../../isvgimage/) contenente contenuto vettoriale da convertire in forme. |
| x | **float** | La coordinata x del frame del gruppo\\u2019s, in punti. |
| y | **float** | La coordinata y del frame del gruppo\\u2019s, in punti. |
| width | **float** | La larghezza del frame del gruppo\\u2019s, in punti. |
| height | **float** | L’altezza del frame del gruppo\\u2019s, in punti. |

### Valore di ritorno

Il nuovo [IGroupShape](../../igroupshape/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGroupShape](../../igroupshape/)
* Classe [IShapeCollection](../)
* Classe [ISvgImage](../../isvgimage/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)