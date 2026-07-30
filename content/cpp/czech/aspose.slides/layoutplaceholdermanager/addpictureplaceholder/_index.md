---
title: AddPicturePlaceholder()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá novou placeholderovou podobu do snímku rozvržení pro vložení obrázku.
type: docs
weight: 53
url: /cs/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metoda

Přidá novou placeholderovou podobu do snímku rozvržení pro vložení obrázku.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Souřadnice X nového placeholder tvaru. |
| y | **float** | Souřadnice Y nového placeholder tvaru. |
| width | **float** | Šířka nového placeholder tvaru. |
| height | **float** | Výška nového placeholder tvaru. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s [Picture](../../picture/) placeholderem.

## Poznámky

Následující příklad ukazuje, jak přidat tvar [Picture](../../picture/) placeholderu do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)