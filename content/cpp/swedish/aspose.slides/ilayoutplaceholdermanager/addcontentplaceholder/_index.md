---
title: AddContentPlaceholder()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, till exempel en bild, tabell, media eller text.
type: docs
weight: 1
url: /sv/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metod

Lägger till en ny platshållarform på layoutbilden för att hålla innehåll, till exempel en bild, tabell, media eller text.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya platshållarformen. |
| y | **float** | Y-koordinaten för den nya platshållarformen. |
| width | **float** | Bredden på den nya platshållarformen. |
| height | **float** | Höjden på den nya platshållarformen. |

### Returvärde

Skapade [IAutoShape](../../iautoshape/) med en Content-platshållare.

## Anmärkningar

Följande exempel visar hur man lägger till Content-platshållarformen på layoutbilden. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [ILayoutPlaceholderManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)