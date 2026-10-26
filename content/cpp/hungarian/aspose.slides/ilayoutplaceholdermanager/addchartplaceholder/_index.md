---
title: AddChartPlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Új helyfoglaló alakzatot ad a elrendezés diára, hogy diagramot tartalmazzon.
type: docs
weight: 66
url: /hu/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metódus

Új helyfoglaló alakzatot ad hozzá a elrendezés diára, amely egy diagramot tartalmaz.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyfoglaló alakzat X koordinátája. |
| y | **float** | Az új helyfoglaló alakzat Y koordinátája. |
| width | **float** | Az új helyfoglaló alakzat szélessége. |
| height | **float** | Az új helyfoglaló alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) Chart helyfoglalóval.

## Megjegyzések

Az alábbi példa bemutatja, hogyan adhatja hozzá a Chart helyfoglaló alakzatot az elrendezés diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)