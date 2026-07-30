---
title: AddPicturePlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar zástupného objektu do rozložení snímku, který bude obsahovat obrázek.
type: docs
weight: 53
url: /cs/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metoda


Přidá nový tvar zástupného objektu na rozložení snímku pro umístění obrázku.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového tvaru zástupného objektu. |
| y | **float** | Souřadnice Y nového tvaru zástupného objektu. |
| width | **float** | Šířka nového tvaru zástupného objektu. |
| height | **float** | Výška nového tvaru zástupného objektu. |

### Návratová hodnota

Vytvořený [IAutoShape](../../iautoshape/) s [Picture](../../picture/) zástupným objektem.
## Poznámky



Níže uvedený příklad ukazuje, jak přidat tvar [Picture](../../picture/) zástupného objektu na rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ILayoutPlaceholderManager](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)