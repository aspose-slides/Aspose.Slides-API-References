---
title: AddTextPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar placeholderu do snímku rozvržení, aby obsahoval textový obsah.
type: docs
weight: 27
url: /cs/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metoda

Přidá nový tvar zástupného znaku do snímku rozvržení, aby obsahoval text.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového placeholderu. |
| y | **float** | Souřadnice Y nového placeholderu. |
| width | **float** | Šířka nového placeholderu. |
| height | **float** | Výška nového placeholderu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s Text placeholderem.
## Poznámky

Následující příklad ukazuje, jak přidat tvar Text placeholderu do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)