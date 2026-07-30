---
title: AddTextPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový placeholder tvar do rozvržení snímku, aby obsahoval textový obsah.
type: docs
weight: 27
url: /cs/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metoda

Přidá nový zástupný tvar do rozložení snímku, aby obsahoval textový obsah.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového zástupného tvaru. |
| y | **float** | Y-souřadnice nového zástupného tvaru. |
| width | **float** | Šířka nového zástupného tvaru. |
| height | **float** | Výška nového zástupného tvaru. |

### Return Value

Vytvořeno [IAutoShape](../../iautoshape/) s Text placeholder.

## Remarks

Následující příklad ukazuje, jak přidat Text placeholder tvar do rozvržení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)