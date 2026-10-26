---
title: InsertConnector()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w określonym indeksie, stosując domyślne stylowanie szablonu.
type: docs
weight: 430
url: /pl/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metoda

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w określonym indeksie, stosując domyślne stylowanie szablonu.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić kształt łącznika. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do wstawienia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metoda

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w określonym indeksie, opcjonalnie stosując domyślne stylowanie szablonu.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić kształt łącznika. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) kształtu łącznika do wstawienia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | **bool** | Prawda, aby zastosować domyślne stylowanie szablonu (niepusta nazwa, prosty styl); fałsz, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)