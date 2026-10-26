---
title: AddContentPlaceholder()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá nový placeholder tvar do snímku rozvržení, který bude obsahovat obsah, například obrázek, tabulku, média nebo text.
type: docs
weight: 1
url: /cs/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metoda

Přidá nový placeholder tvar do snímku rozvržení, který bude obsahovat obsah, například obrázek, tabulku, média nebo text.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového placeholder tvaru. |
| y | **float** | Y-souřadnice nového placeholder tvaru. |
| width | **float** | Šířka nového placeholder tvaru. |
| height | **float** | Výška nového placeholder tvaru. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s Content placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar Content placeholder do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)