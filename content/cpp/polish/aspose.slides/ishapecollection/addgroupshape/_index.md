---
title: AddGroupShape()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. Ramka grupy zostanie automatycznie dopasowana, aby pomieścić wszystkie dodane do niej kształty.
type: docs
weight: 352
url: /pl/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metoda

Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. Ramka grupy zostanie automatycznie dopasowana, aby pomieścić wszystkie dodane do niej kształty.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Wartość zwracana

Nowo utworzony [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metoda

Tworzy nowy kształt grupy, konwertuje określony obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Obiekt [ISvgImage](../../isvgimage/) zawierający treść wektorową do konwersji na kształty. |
| x | **float** | Współrzędna x ramki grupy, w punktach. |
| y | **float** | Współrzędna y ramki grupy, w punktach. |
| width | **float** | Szerokość ramki grupy, w punktach. |
| height | **float** | Wysokość ramki grupy, w punktach. |

### Wartość zwracana

Nowo utworzony [IGroupShape](../../igroupshape/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IGroupShape](../../igroupshape/)
* Klasa [IShapeCollection](../)
* Klasa [ISvgImage](../../isvgimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)