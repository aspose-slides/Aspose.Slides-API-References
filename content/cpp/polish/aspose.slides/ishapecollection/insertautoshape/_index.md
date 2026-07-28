---
title: InsertAutoShape()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod podanym indeksem, stosując formatowanie szablonu domyślnego.
type: docs
weight: 339
url: /pl/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod podanym indeksem, stosując formatowanie szablonu domyślnego.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zero-bazowy, pod którym ma zostać wstawiony nowy kształt automatyczny. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto-kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie inicjalizując go stylem szablonu domyślnego.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zero-bazowy, pod którym ma zostać wstawiony kształt automatyczny. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto-kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | **bool** | true, aby zastosować domyślne formatowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)