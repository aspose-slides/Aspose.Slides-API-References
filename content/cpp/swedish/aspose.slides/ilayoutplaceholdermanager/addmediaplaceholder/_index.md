---
title: AddMediaPlaceholder()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny platshållarform på layoutbilden för att hålla ett mediaobjekt.
type: docs
weight: 105
url: /sv/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) method


Lägger till en ny platshållarform på layoutbilden för att hålla ett mediaobjekt.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya platshållarformen. |
| y | **float** | Y-koordinaten för den nya platshållarformen. |
| width | **float** | Bredden på den nya platshållarformen. |
| height | **float** | Höjden på den nya platshållarformen. |

### Returvärde

Skapade [IAutoShape](../../iautoshape/) med en Media-platshållare.
## Anmärkningar



Följande exempel visar hur man lägger till Media-platshållarformen på layoutbilden. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [ILayoutPlaceholderManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)