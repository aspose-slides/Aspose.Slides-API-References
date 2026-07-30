---
title: AddTablePlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový placeholder tvar do rozložení snímku, aby obsahoval tabulku.
type: docs
weight: 79
url: /cs/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) metoda

Přidá nový placeholder tvar do rozložení snímku, aby obsahoval tabulku.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X souřadnice nového placeholder tvaru. |
| y | **float** | Y souřadnice nového placeholder tvaru. |
| width | **float** | Šířka nového placeholder tvaru. |
| height | **float** | Výška nového placeholder tvaru. |

### Návratová hodnota

Vytvořen [IAutoShape](../../iautoshape/) s [Table](../../table/) placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat [Table](../../table/) placeholder tvar do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)