---
title: AddAutoShape()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.
type: docs
weight: 352
url: /pl/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metoda


Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto-kształtu do dodania. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metoda


Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto-kształtu do dodania. |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | **bool** | True, aby zastosować domyślny styl szablonu (prosty styl, wyśrodkowany tekst i niepustą nazwę) do nowego kształtu; false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na ich wartości domyślne. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).

## Zobacz także

* Wyliczenie [ShapeType](../../shapetype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)