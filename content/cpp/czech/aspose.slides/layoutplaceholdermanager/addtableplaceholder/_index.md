---
title: AddTablePlaceholder()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá nový tvar zástupné položky do rozložení snímku pro umístění tabulky.
type: docs
weight: 79
url: /cs/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) metoda

Přidá novou tvarovou zástupnou položku do rozložení snímku pro umístění tabulky.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X souřadnice nového tvaru zástupné položky. |
| y | **float** | Y souřadnice nového tvaru zástupné položky. |
| width | **float** | Šířka nového tvaru zástupné položky. |
| height | **float** | Výška nového tvaru zástupné položky. |

### Návratová hodnota

Vytvořený [IAutoShape](../../iautoshape/) s [Table](../../table/) zástupnou položkou.

## Poznámky

Následující příklad ukazuje, jak přidat tvar [Table](../../table/) zástupné položky do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)