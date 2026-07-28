---
title: AddChartPlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Új helyfoglaló alakzatot ad a layout diához, hogy egy diagramot tartalmazzon.
type: docs
weight: 66
url: /hu/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metódus


Új helyfoglaló alakzatot ad a layout diához, hogy egy Chart-ot tartalmazzon.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
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



A következő példa azt mutatja, hogyan kell hozzáadni a Chart helyfoglaló alakzatot a layout diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)