---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá nový tvar placeholderu do rozvržení snímku pro uchování online obrázku.
type: docs
weight: 118
url: /cs/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metoda

Přidá nový placeholder tvar do rozvržení snímku pro uchování online obrázku.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového placeholderu. |
| y | **float** | Y-souřadnice nového placeholderu. |
| width | **float** | Šířka nového placeholderu. |
| height | **float** | Výška nového placeholderu. |

### Návratová hodnota

Vytvořen [IAutoShape](../../iautoshape/) s online obrázkovým placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar placeholderu online obrázku do rozvržení snímku.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)