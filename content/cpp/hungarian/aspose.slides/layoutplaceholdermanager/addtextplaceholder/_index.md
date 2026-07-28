---
title: AddTextPlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Új helykitöltő alakzatot ad a layout diához, amely szövegtartalmat tartalmaz.
type: docs
weight: 27
url: /hu/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metódus

Új helykitöltő alakzatot ad a layout diához, amely szövegtartalmat tartalmaz.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy szöveghelykitöltővel.

## Megjegyzés

Az alábbi példa megmutatja, hogyan adhatunk hozzá egy szöveghelykitöltő alakzatot a layout diához. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)