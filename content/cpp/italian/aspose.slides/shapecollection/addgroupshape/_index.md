---
title: AddGroupShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.
type: docs
weight: 391
url: /it/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() metodo


Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Valore restituito

Il [IGroupShape](../../igroupshape/) appena creato.
## Osservazioni



L’esempio seguente mostra come aggiungere una forma di gruppo a una diapositiva di PowerPoint [Presentation](../../presentation/). 
```cpp
// Istanzia la classe Presentation
auto pres = System::MakeObject<Presentation>();

// Ottieni la prima diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Accesso alla raccolta di forme delle diapositive
auto slideShapes = slide->get_Shapes();
// Aggiunta di una forma di gruppo alla diapositiva
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Aggiunta di forme all'interno della forma di gruppo aggiunta
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Aggiunta del riquadro della forma di gruppo
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Scrivi il file PPTX su disco
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metodo


Crea una nuova forma di gruppo, converte l’immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della raccolta di forme.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Il [ISvgImage](../../isvgimage/) contenente contenuto vettoriale da convertire in forme. |
| x | **float** | La coordinata x del riquadro del gruppo, in punti. |
| y | **float** | La coordinata y del riquadro del gruppo, in punti. |
| width | **float** | La larghezza del riquadro del gruppo, in punti. |
| height | **float** | L’altezza del riquadro del gruppo, in punti. |

### Valore restituito

Il [IGroupShape](../../igroupshape/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)