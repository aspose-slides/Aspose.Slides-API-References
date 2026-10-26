---
title: AddConnector()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów.
type: docs
weight: 417
url: /pl/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) metoda

Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) łącznika do dodania. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## Uwagi

Poniższy przykład pokazuje, jak dodać łącznik (zagięty łącznik) między dwoma kształtami (elipsą i prostokątem) w programie PowerPoint [Presentation](../../presentation/). 
```cpp
// Tworzy instancję klasy prezentacji reprezentującej plik PPTX
auto input = System::MakeObject<Presentation>();

// Uzyskuje dostęp do kolekcji kształtów konkretnego slajdu
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Dodaje automatyczny kształt elipsy
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Dodaje automatyczny kształt prostokąta
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Dodaje kształt łącznika do kolekcji kształtów slajdu
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Łączy kształty przy użyciu łącznika
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Wywołuje metodę reroute, która ustawia automatyczną najkrótszą ścieżkę pomiędzy kształtami
connector->Reroute();

// Zapisuje prezentację
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metoda

Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylizowanie szablonu.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) łącznika do utworzenia. |
| x | **float** | Współrzędna x ramki łącznika, w punktach. |
| y | **float** | Współrzędna y ramki łącznika, w punktach. |
| width | **float** | Szerokość ramki łącznika, w punktach. |
| height | **float** | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | **bool** | True, aby zastosować domyślne stylizowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

### Wartość zwracana

Nowo utworzony [IConnector](../../iconnector/).

## Zobacz także

* Wyliczenie [ShapeType](../../shapetype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IConnector](../../iconnector/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)