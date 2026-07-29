---
title: AddTablePlaceholder()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny platshållarform på layoutbilden för att hålla en tabell.
type: docs
weight: 79
url: /sv/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) metod

Lägger till en ny platshållarform på layoutbilden för att hålla en tabell.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya platshållarformen. |
| y | **float** | Y-koordinaten för den nya platshållarformen. |
| width | **float** | Bredden på den nya platshållarformen. |
| height | **float** | Höjden på den nya platshållarformen. |

### Returvärde

Skapade [IAutoShape](../../iautoshape/) med en [Table](../../table/) platshållare.

## Anmärkningar

Följande exempel visar hur man lägger till [Table](../../table/) platshållarformen till layoutbilden. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [LayoutPlaceholderManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)