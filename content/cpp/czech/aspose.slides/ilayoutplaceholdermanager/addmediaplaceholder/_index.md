---
title: AddMediaPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar zástupného symbolu do rozložení snímku, aby obsahoval mediální objekt.
type: docs
weight: 105
url: /cs/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) metoda

Přidá nový tvar zástupného symbolu do rozložení snímku, aby obsahoval mediální objekt.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového tvaru zástupného symbolu. |
| y | **float** | Y-souřadnice nového tvaru zástupného symbolu. |
| width | **float** | Šířka nového tvaru zástupného symbolu. |
| height | **float** | Výška nového tvaru zástupného symbolu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s mediálním zástupným symbolem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar mediálního zástupného symbolu do rozložení snímku.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)