---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá nový tvar zástupného objektu do rozložení snímku, aby obsahoval text ve svislém směru.
type: docs
weight: 40
url: /cs/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) metoda


Přidá nový tvar zástupného objektu do rozložení snímku, aby obsahoval text ve svislém směru.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Souřadnice X nového tvaru zástupného objektu. |
| y | **float** | Souřadnice Y nového tvaru zástupného objektu. |
| width | **float** | Šířka nového tvaru zástupného objektu. |
| height | **float** | Výška nového tvaru zástupného objektu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s Text (Vertical) placeholder.

## Poznámky



Následující příklad ukazuje, jak přidat tvar Text (Vertical) placeholder do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [LayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)