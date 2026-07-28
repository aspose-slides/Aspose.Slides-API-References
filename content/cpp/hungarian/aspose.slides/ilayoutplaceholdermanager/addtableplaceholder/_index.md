---
title: AddTablePlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Új helyőrző alakzatot ad a elrendezési diára, amely táblázatot tartalmaz.
type: docs
weight: 79
url: /hu/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) method


Új helyőrző alakzatot ad a elrendezési diára, amely táblázatot tartalmaz.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyőrző alakzat X koordinátája. |
| y | **float** | Az új helyőrző alakzat Y koordinátája. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Return Value

Létrehozott [IAutoShape](../../iautoshape/) egy [Table](../../table/) helyőrzővel.
## Megjegyzések



Az alábbi példa bemutatja, hogyan adható hozzá a [Table](../../table/) helyőrző alakzat az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)