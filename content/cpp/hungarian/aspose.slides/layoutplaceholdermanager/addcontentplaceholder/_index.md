---
title: AddContentPlaceholder()
second_title: Aspose.Slides C++ API referencia
description: Új helykitöltő alakzatot ad a elrendezési diára, amely tartalmat tartalmaz, például képet, táblázatot, médiát vagy szöveget.
type: docs
weight: 1
url: /hu/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metódus

Új helykitöltő alakzatot ad hozzá az elrendezési diához, hogy tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmazzon.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy Content helykitöltővel.

## Megjegyzések

A következő példa bemutatja, hogyan adhatja hozzá a Content helykitöltő alakzatot a layout diára. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)