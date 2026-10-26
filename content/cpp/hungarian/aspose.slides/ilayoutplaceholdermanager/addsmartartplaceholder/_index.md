---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Új helyőrző alakzatot ad hozzá az elrendezési diára, hogy egy SmartArt diagramot tartalmazzon.
type: docs
weight: 92
url: /hu/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metódus


Új helyőrző alakzatot ad hozzá az elrendezési diára, hogy egy [SmartArt](../../../aspose.slides.smartart/) diagramot tartalmazzon.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Az X koordináta az új helyőrző alakzatra. |
| y | **float** | Az Y koordináta az új helyőrző alakzatra. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy [SmartArt](../../../aspose.slides.smartart/) helyőrzővel.
## Megjegyzések



Az alábbi példa bemutatja, hogyan lehet hozzáadni a [SmartArt](../../../aspose.slides.smartart/) helyőrző alakzatot az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)