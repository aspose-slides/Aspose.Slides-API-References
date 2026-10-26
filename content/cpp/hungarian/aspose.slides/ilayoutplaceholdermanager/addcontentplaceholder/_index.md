---
title: AddContentPlaceholder()
second_title: Aspose.Slides a C++ API referenciája
description: Új helyőrző alakzatot ad a elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz.
type: docs
weight: 1
url: /hu/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metódus

Új helyőrző alakzatot ad a elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyőrző alakzat X koordinátája. |
| y | **float** | Az új helyőrző alakzat Y koordinátája. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy Content helyőrzővel.

## Megjegyzések

A következő példa azt mutatja, hogyan lehet hozzáadni a Content helyőrző alakzatot az elrendezési diához.  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)