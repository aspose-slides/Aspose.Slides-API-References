---
title: InsertAutoShape()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów w określonym indeksie, stosując domyślne formatowanie szablonu.
type: docs
weight: 378
url: /pl/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method


Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów w określonym indeksie, stosując domyślne formatowanie szablonu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiony nowy kształt automatyczny. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatycznego kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method


Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów w określonym indeksie, opcjonalnie inicjalizując go domyślnym stylowaniem szablonu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiony kształt automatyczny. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) automatycznego kształtu do wstawienia. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | **bool** | Prawda, aby zastosować domyślne stylowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); fałsz, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na domyślne. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## Zobacz także

* Wyliczenie [ShapeType](../../shapetype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)