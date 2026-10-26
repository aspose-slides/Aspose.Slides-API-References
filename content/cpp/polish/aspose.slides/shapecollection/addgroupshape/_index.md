---
title: AddGroupShape()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy nowy pusty kształt grupowy i dodaje go na koniec kolekcji kształtów. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie kształty dodane do niej.
type: docs
weight: 391
url: /pl/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method


Tworzy nowy pusty kształt grupowy i dodaje go na koniec kolekcji kształtów. Ramka grupy będzie automatycznie dostosowywać się, aby pomieścić wszystkie kształty dodane do niej.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Return Value

Nowo utworzony [IGroupShape](../../igroupshape/).
## Remarks



Poniższy przykład pokazuje, jak dodać kształt grupowy do slajdu programu PowerPoint [Presentation](../../presentation/). 
```cpp
// Utwórz instancję klasy Presentation
auto pres = System::MakeObject<Presentation>();

// Pobierz pierwszy slajd
auto slide = pres->get_Slides()->idx_get(0);
// Dostęp do kolekcji kształtów slajdów
auto slideShapes = slide->get_Shapes();
// Dodawanie kształtu grupowego do slajdu
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Dodawanie kształtów do dodanej grupy
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Dodawanie ramki kształtu grupowego
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Zapisz plik PPTX na dysk
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Tworzy nowy kształt grupowy, konwertuje podany obraz SVG na pojedyncze kształty i dodaje powstałą grupę na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) zawierający zawartość wektorową do konwersji na kształty. |
| x | **float** | Współrzędna x ramki grupy, w punktach. |
| y | **float** | Współrzędna y ramki grupy, w punktach. |
| width | **float** | Szerokość ramki grupy, w punktach. |
| height | **float** | Wysokość ramki grupy, w punktach. |

### Return Value

Nowo utworzony [IGroupShape](../../igroupshape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)