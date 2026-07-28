---
title: AddMediaPlaceholder()
second_title: Aspose.Slides C++ API hivatkozás
description: Új helykitöltő alakzatot ad a layout diához, hogy egy médiaobjektumot tároljon.
type: docs
weight: 105
url: /hu/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) method

Új helykitöltő alakzatot ad hozzá az elrendezésdiához egy médiaobjektum tárolásához.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új helykitöltő alakzat X koordinátája. |
| y | **float** | Az új helykitöltő alakzat Y koordinátája. |
| width | **float** | Az új helykitöltő alakzat szélessége. |
| height | **float** | Az új helykitöltő alakzat magassága. |

### Visszatérési érték

Létrehozott [IAutoShape](../../iautoshape/) egy Media helykitöltővel.

## Megjegyzések

A következő példa bemutatja, hogyan lehet hozzáadni a Media helykitöltő alakzatot az elrendezésdiához.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)