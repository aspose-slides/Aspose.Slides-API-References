---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.
type: docs
weight: 183
url: /aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method


Determines whether the two [IBaseSlide](../) instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | The [IBaseSlide](../) to compare with the current [IBaseSlide](../). |

### Return Value

**true** if the specified [IBaseSlide](../) is equal to the current [IBaseSlide](../); otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)