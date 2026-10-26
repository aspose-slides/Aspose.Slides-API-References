---
title: AddPicturePlaceholder()
second_title: Aspose.Slides C++ API Referencia
description: Új helyfoglaló alakzatot ad az elrendezés diához, hogy képet tartalmazzon.
type: docs
weight: 53
url: /hu/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metódus


Új helyfoglaló alakzatot ad az elrendezés diához, amely a képet tartalmazza.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helyfoglaló alakzat X koordinátája. |
| y | **float** | Az új helyfoglaló alakzat Y koordinátája. |
| width | **float** | Az új helyfoglaló alakzat szélessége. |
| height | **float** | Az új helyfoglaló alakzat magassága. |

### Visszatérési érték

Létrehozva [IAutoShape](../../iautoshape/) egy [Picture](../../picture/) helyfoglalóval.

## Megjegyzések



A következő példa megmutatja, hogyan adhatunk hozzá egy [Picture](../../picture/) helyfoglaló alakzatot az elrendezés diára. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)