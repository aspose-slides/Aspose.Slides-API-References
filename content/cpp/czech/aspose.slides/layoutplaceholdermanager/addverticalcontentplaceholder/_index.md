---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá nový tvar placeholderu do snímku rozložení, který bude obsahovat obsah, například obrázek, tabulku, média nebo text ve svislém směru.
type: docs
weight: 14
url: /cs/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) method

Přidá nový tvar placeholderu do rozložení snímku, který bude obsahovat obsah, například obrázek, tabulku, média nebo text ve svislém směru.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s placeholderem Content (Vertical).

## Poznámky

Následující příklad ukazuje, jak přidat tvar placeholderu Content (Vertical) do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)