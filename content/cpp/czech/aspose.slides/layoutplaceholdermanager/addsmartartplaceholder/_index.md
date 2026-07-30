---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá nový tvar zástupce do snímku rozvržení, aby obsahoval diagram SmartArt.
type: docs
weight: 92
url: /cs/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metoda

Přidá nový tvar zástupce do rozvržení snímku, aby obsahoval diagram [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X souřadnice nového tvaru zástupce. |
| y | **float** | Y souřadnice nového tvaru zástupce. |
| width | **float** | Šířka nového tvaru zástupce. |
| height | **float** | Výška nového tvaru zástupce. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s [SmartArt](../../../aspose.slides.smartart/) zástupcem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar zástupce [SmartArt](../../../aspose.slides.smartart/) do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)