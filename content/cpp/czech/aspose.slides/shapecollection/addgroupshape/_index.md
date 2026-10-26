---
title: AddGroupShape()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary.
type: docs
weight: 391
url: /cs/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() metoda

Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí tak, aby obsahoval všechny přidané tvary.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Návratová hodnota

Nově vytvořený [IGroupShape](../../igroupshape/).

## Poznámky

Následující příklad ukazuje, jak přidat skupinový tvar do snímku PowerPoint [Presentation](../../presentation/). 
```cpp
// Vytvořte instanci třídy Presentation
auto pres = System::MakeObject<Presentation>();

// Získat první snímek
auto slide = pres->get_Slides()->idx_get(0);
// Přístup ke kolekci tvarů snímků
auto slideShapes = slide->get_Shapes();
// Přidání skupinového tvaru do snímku
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Přidání tvarů do přidaného skupinového tvaru
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Přidání rámce skupinového tvaru
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Zapsat soubor PPTX na disk
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metoda

Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá výslednou skupinu na konec kolekce tvarů.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) obsahující vektorový obsah k převodu na tvary. |
| x | **float** | Souřadnice x rámce skupiny, v bodech. |
| y | **float** | Souřadnice y rámce skupiny, v bodech. |
| width | **float** | Šířka rámce skupiny, v bodech. |
| height | **float** | Výška rámce skupiny, v bodech. |

### Návratová hodnota

Nově vytvořený [IGroupShape](../../igroupshape/).

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IGroupShape](../../igroupshape/)
* Třída [ShapeCollection](../)
* Třída [ISvgImage](../../isvgimage/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)