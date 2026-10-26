---
title: Shapes()
second_title: Aspose.Slides C++ API Referenciája
description: A Presentation-ben található összes Shape példányt összegyűjti.
type: docs
weight: 1
url: /hu/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metódus


Az [Shape](../../../aspose.slides/shape/) összes példányát összegyűjti a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) az alakzatok összegyűjtéséhez |

### Visszatérési érték

A prezentációban található összes alakzat gyűjteménye
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ha a shape AutoShape, fekete szilárd keretet adunk hozzá
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




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [Shape](../../../aspose.slides/shape/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [Collect](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)