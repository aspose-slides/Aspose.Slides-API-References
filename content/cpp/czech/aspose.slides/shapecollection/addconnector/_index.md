---
title: AddConnector()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří nový tvar konektoru s výchozím šablonovým stylováním a přidá jej na konec kolekce tvarů.
type: docs
weight: 417
url: /cs/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Vytvoří nový tvar konektoru s výchozím šablonovým stylováním a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) konektoru, který se má přidat. |
| x | **float** | x-souřadnice rámce konektoru, v bodech. |
| y | **float** | y-souřadnice rámce konektoru, v bodech. |
| width | **float** | šířka rámce konektoru, v bodech. |
| height | **float** | výška rámce konektoru, v bodech. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).
## Poznámky



Následující příklad ukazuje, jak přidat konektor (ohnutý konektor) mezi dva tvary (elipsu a obdélník) v PowerPointu [Presentation](../../presentation/). 
```cpp
// Vytvoří instanci třídy prezentace, která představuje soubor PPTX
auto input = System::MakeObject<Presentation>();

// Přistupuje ke kolekci tvarů pro konkrétní snímek
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Přidá automatický tvar Elipsa
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Přidá automatický tvar Obdélník
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Přidá tvar konektoru do kolekce tvarů snímku
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Propojí tvary pomocí konektoru
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Volá Reroute, který nastaví automatickou nejkratší cestu mezi tvary
connector->Reroute();

// Uloží prezentaci
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Vytvoří nový tvar konektoru a přidá jej na konec kolekce tvarů, volitelně použije výchozí šablonové stylování.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) konektoru, který se má vytvořit. |
| x | **float** | x-souřadnice rámce konektoru, v bodech. |
| y | **float** | y-souřadnice rámce konektoru, v bodech. |
| width | **float** | šířka rámce konektoru, v bodech. |
| height | **float** | výška rámce konektoru, v bodech. |
| createFromTemplate | **bool** | True pro použití výchozího šablonového stylování (neprázdný název, jednoduchý styl); false pro vytvoření konektoru s výchozími hodnotami vlastností. |

### Návratová hodnota

Nově vytvořený [IConnector](../../iconnector/).

## Viz také

* Výčet [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IConnector](../../iconnector/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)