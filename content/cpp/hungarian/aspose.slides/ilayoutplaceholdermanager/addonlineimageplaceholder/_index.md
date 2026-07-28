---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Új helykitöltő alakzatot ad a elrendezési diára, hogy online képet tartalmazzon.
type: docs
weight: 118
url: /hu/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metódus

Új helykitöltő alakzatot ad a elrendezési diára, hogy online képet tartalmazzon.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy online kép helykitöltővel.

## Megjegyzések

A következő példa bemutatja, hogyan adható hozzá az online kép helykitöltő alakzat az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)