---
title: InsertConnector()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem, stosując domyślne formatowanie szablonu.
type: docs
weight: 391
url: /pl/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metoda

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem, stosując domyślne formatowanie szablonu.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym należy wstawić kształt łącznika. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do wstawienia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metoda

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów pod określonym indeksem, opcjonalnie stosując domyślne formatowanie szablonu.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym należy wstawić kształt łącznika. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do wstawienia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | **bool** | True, aby zastosować domyślne formatowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)