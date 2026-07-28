---
title: AddConnector()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nowy kształt łącznika z domyślnym stylem szablonu i dodaje go na koniec kolekcji kształtów.
type: docs
weight: 378
url: /pl/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metoda

Tworzy nowy kształt łącznika z domyślnym stylem szablonu i dodaje go na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do dodania. |
| x | **float** | Współrzędna x ramki connector\u2019s, w punktach. |
| y | **float** | Współrzędna y ramki connector\u2019s, w punktach. |
| width | **float** | Szerokość ramki connector\u2019s, w punktach. |
| height | **float** | Wysokość ramki connector\u2019s, w punktach. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metoda

Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślny styl szablonu.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do utworzenia. |
| x | **float** | Współrzędna x ramki connector\u2019s, w punktach. |
| y | **float** | Współrzędna y ramki connector\u2019s, w punktach. |
| width | **float** | Szerokość ramki connector\u2019s, w punktach. |
| height | **float** | Wysokość ramki connector\u2019s, w punktach. |
| createFromTemplate | **bool** | True, aby zastosować domyślny styl szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)