---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides C++ API Referencia
description: Új helyőrző alakzatot ad az elrendezési diára, hogy függőleges irányban tartsa a szövegtartalmat.
type: docs
weight: 40
url: /hu/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) módszer

Új helyőrző alakzatot ad az elrendezési diára, hogy függőleges irányban tartsa a szövegtartalmat.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyőrző alakzat X koordinátája. |
| y | **float** | Az új helyőrző alakzat Y koordinátája. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy Szöveg (függőleges) helyőrzővel.

## Megjegyzés

Az alábbi példa bemutatja, hogyan adhatunk hozzá egy Szöveg (függőleges) helyőrző alakzatot az elrendezési diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)