---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides C++ API Referencia
description: Új helyőrző alakzatot ad az elrendezési diához, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tárol függőleges irányban.
type: docs
weight: 14
url: /hu/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metódus

Új helyőrző alakzatot ad a elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tárol függőleges irányban.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Az új helyőrző alakzat X koordinátája. |
| y | **float** | Az új helyőrző alakzat Y koordinátája. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy Content (Vertical) helyőrzővel.

## Megjegyzések

A következő példa bemutatja, hogyan adhatja hozzá a Content (Vertical) helyőrző alakzatot az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)