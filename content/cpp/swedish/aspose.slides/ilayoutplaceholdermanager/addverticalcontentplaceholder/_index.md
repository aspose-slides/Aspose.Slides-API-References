---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny platshållarform till layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text i vertikal riktning.
type: docs
weight: 14
url: /sv/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metod

Lägger till en ny platshållarform till layoutbilden för att hålla innehåll, såsom en bild, tabell, media eller text i vertikal riktning.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya platshållarformen. |
| y | **float** | Y-koordinaten för den nya platshållarformen. |
| width | **float** | Bredden på den nya platshållarformen. |
| height | **float** | Höjden på den nya platshållarformen. |

### Returvärde

Skapade [IAutoShape](../../iautoshape/) med en Content (Vertical) platshållare.

## Anmärkningar

Följande exempel visar hur man lägger till Content (Vertical) platshållarformen till layoutbilden. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [ILayoutPlaceholderManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)