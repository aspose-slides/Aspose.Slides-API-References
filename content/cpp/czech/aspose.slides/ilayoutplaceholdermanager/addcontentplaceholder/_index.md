---
title: AddContentPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar placeholderu do snímku rozvržení, který bude sloužit k uchování obsahu, například obrázku, tabulky, multimédií nebo textu.
type: docs
weight: 1
url: /cs/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metoda

Přidá nový tvar placeholderu do snímku rozvržení, který bude sloužit k uchování obsahu, například obrázek, tabulku, multimédia nebo text.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového tvaru placeholderu. |
| y | **float** | Y-souřadnice nového tvaru placeholderu. |
| width | **float** | Šířka nového tvaru placeholderu. |
| height | **float** | Výška nového tvaru placeholderu. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s placeholderem obsahu.

## Poznámky

Následující příklad ukazuje, jak přidat tvar placeholderu Content do snímku rozvržení. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)