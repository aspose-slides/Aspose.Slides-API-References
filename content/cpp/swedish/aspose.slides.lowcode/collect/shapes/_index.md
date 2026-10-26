---
title: Shapes()
second_title: Aspose.Slides för C++ API-referens
description: Samlar alla instanser av Shape i Presentationen.
type: docs
weight: 1
url: /sv/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metod


Samlar alla instanser av [Shape](../../../aspose.slides/shape/) i [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) för att samla former |

### Returvärde

Samling av alla former som finns i presentationen
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // om formen är AutoShape, lägg till en svart solid kant
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klass [Shape](../../../aspose.slides/shape/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [Collect](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)