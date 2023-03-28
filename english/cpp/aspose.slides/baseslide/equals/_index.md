---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.
type: docs
weight: 170
url: /cpp/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals([System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\>) method


Determines whether the two [IBaseSlide](../../ibaseslide/) instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | The [IBaseSlide](../../ibaseslide/) to compare with the current [IBaseSlide](../../ibaseslide/). |

### Return Value

**true** if the specified [IBaseSlide](../../ibaseslide/) is equal to the current [IBaseSlide](../../ibaseslide/); otherwise, **false**.
## Remarks



The following example shows how to compare two slides. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../../ibaseslide/)
* Class [BaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
