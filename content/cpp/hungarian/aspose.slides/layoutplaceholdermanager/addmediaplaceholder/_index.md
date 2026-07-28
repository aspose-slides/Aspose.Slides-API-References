---
title: AddMediaPlaceholder()
second_title: Aspose.Slides a C++ API referencia
description: Új helyőrző alakzatot ad a layout diához egy média objektum tárolásához.
type: docs
weight: 105
url: /hu/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) módszer

Új helyőrző alakzatot ad a layout diához egy média objektum tárolásához.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az X koordináta az új helyőrző alakzatnál. |
| y | **float** | Az Y koordináta az új helyőrző alakzatnál. |
| width | **float** | Az új helyőrző alakzat szélessége. |
| height | **float** | Az új helyőrző alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy média helyőrzővel.

## Megjegyzések

Az alábbi példa bemutatja, hogyan lehet hozzáadni a média helyőrző alakzatot a layout diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)