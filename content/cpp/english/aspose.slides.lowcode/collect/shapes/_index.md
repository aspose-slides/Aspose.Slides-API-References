---
title: Shapes()
second_title: Aspose.Slides for C++ API Reference
description: Collects all instances of Shape in the Presentation.
type: docs
weight: 1
url: /aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) method


Collects all instances of [Shape](../../../aspose.slides/shape/) in the [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to collect shapes |

### Return Value

Collection of all shapes that contain in the presentation
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // if the shape is AutoShape, add a black solid border
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




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Shape](../../../aspose.slides/shape/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [Collect](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)