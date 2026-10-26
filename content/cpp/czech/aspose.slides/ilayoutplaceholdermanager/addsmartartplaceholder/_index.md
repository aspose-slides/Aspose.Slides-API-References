---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides pro C++ referenci API
description: Přidá nový tvar zástupce do snímku rozložení, aby obsahoval diagram SmartArt.
type: docs
weight: 92
url: /cs/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metoda

Přidá nový tvar zástupce do snímku rozložení, který bude obsahovat diagram [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
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

Následující příklad ukazuje, jak přidat tvar [SmartArt](../../../aspose.slides.smartart/) zástupce do snímku rozložení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)