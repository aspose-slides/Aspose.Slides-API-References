---
title: Shapes()
second_title: Aspose.Slides pro C++ API Reference
description: Shromažďuje všechny instance Shape v Presentation.
type: docs
weight: 1
url: /cs/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metoda


Shromažďuje všechny instance [Shape](../../../aspose.slides/shape/) v [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) pro shromažďování tvarů |

### Návratová hodnota

Kolekce všech tvarů, které jsou v prezentaci
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // pokud je tvar AutoShape, přidejte černý plný okraj
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




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Třída [Shape](../../../aspose.slides/shape/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [Collect](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)