---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Új helykitöltő alakzatot ad a layout diára, hogy egy SmartArt diagramot tartalmazzon.
type: docs
weight: 92
url: /hu/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method


Új helykitöltő alakzatot ad a layout diára, hogy egy [SmartArt](../../../aspose.slides.smartart/) diagramot tartalmazzon.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy [SmartArt](../../../aspose.slides.smartart/) helykitöltővel.
## Megjegyzés



Az alábbi példa bemutatja, hogyan lehet hozzáadni a [SmartArt](../../../aspose.slides.smartart/) helykitöltő alakzatot a layout diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)