---
title: AddMediaPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar zástupce do rozvržení snímku, který bude obsahovat mediální objekt.
type: docs
weight: 105
url: /cs/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) metoda


Přidá nový tvar zástupce do rozvržení snímku, aby obsahoval Media objekt.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X souřadnice nového tvaru zástupce. |
| y | **float** | Y souřadnice nového tvaru zástupce. |
| width | **float** | Šířka nového tvaru zástupce. |
| height | **float** | Výška nového tvaru zástupce. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s Media zástupcem.
## Poznámky



Následující příklad ukazuje, jak přidat tvar Media placeholder do rozvržení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)