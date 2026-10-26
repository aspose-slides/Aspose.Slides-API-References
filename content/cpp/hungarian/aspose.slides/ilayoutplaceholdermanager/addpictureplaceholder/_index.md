---
title: AddPicturePlaceholder()
second_title: Aspose.Slides C++ API referenciája
description: Új helyőrző alakzatot ad a elrendezési diához, amely képet tartalmaz.
type: docs
weight: 53
url: /hu/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metódus

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely egy képet tartalmaz.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyőrző alakzat X koordinátája. |
| y | **float** | Az új helyőrző alakzat Y koordinátája. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy [Picture](../../picture/) helyőrzővel.

## Megjegyzés



A következő példa bemutatja, hogyan adhatunk hozzá a [Picture](../../picture/) helyőrző alakzatot az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ILayoutPlaceholderManager](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)