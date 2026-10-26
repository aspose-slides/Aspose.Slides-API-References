---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Új helykitöltő alakzatot ad hozzá az elrendezés diára, hogy függőlegesen tartalmat, például képet, táblázatot, médiát vagy szöveget tároljon.
type: docs
weight: 14
url: /hu/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metódus

Új helykitöltő alakzatot ad hozzá a elrendezés diára, hogy függőlegesen tartalmat, például képet, táblázatot, médiát vagy szöveget tároljon.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

[IAutoShape](../../iautoshape/) létrehozva egy tartalom (függőleges) helykitöltővel.

## Megjegyzés

A következő példa bemutatja, hogyan adható a tartalom (függőleges) helykitöltő alakzat az elrendezés diához.  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [LayoutPlaceholderManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)