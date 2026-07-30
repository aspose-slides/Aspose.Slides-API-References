---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides pro C++ API Referenci
description: Přidá nový tvar zástupného objektu do snímku rozvržení, aby uchovával obsah, například obrázek, tabulku, média nebo text ve svislém směru.
type: docs
weight: 14
url: /cs/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metoda


Přidá nový tvar zástupného objektu do snímku rozvržení, aby uchovával obsah, například obrázek, tabulku, média nebo text ve svislém směru.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X souřadnice nového tvaru zástupného objektu. |
| y | **float** | Y souřadnice nového tvaru zástupného objektu. |
| width | **float** | Šířka nového tvaru zástupného objektu. |
| height | **float** | Výška nového tvaru zástupného objektu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s obsahovým (vertikálním) zástupným objektem.
## Poznámky



Následující příklad ukazuje, jak přidat obsahový (vertikální) zástupný tvar do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)