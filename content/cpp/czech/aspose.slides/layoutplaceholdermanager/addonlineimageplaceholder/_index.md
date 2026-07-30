---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar placeholderu do rozvržení snímku pro uložení online obrázku.
type: docs
weight: 118
url: /cs/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metoda

Přidá nový tvar placeholderu do rozvržení snímku pro uložení online obrázku.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového tvaru placeholderu. |
| y | **float** | Souřadnice Y nového tvaru placeholderu. |
| width | **float** | Šířka nového tvaru placeholderu. |
| height | **float** | Výška nového tvaru placeholderu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s online obrázkovým placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar placeholderu online obrázku do rozvržení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)