---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá nový tvar zástupce do rozvržení snímku, aby držel textový obsah ve svislém směru.
type: docs
weight: 40
url: /cs/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) metoda

Přidá nový tvar zástupce do rozvržení snímku, aby držel textový obsah ve svislém směru.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového tvaru zástupce. |
| y | **float** | Souřadnice Y nového tvaru zástupce. |
| width | **float** | Šířka nového tvaru zástupce. |
| height | **float** | Výška nového tvaru zástupce. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s Text (Vertical) placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar Text (Vertical) placeholder do rozvržení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)