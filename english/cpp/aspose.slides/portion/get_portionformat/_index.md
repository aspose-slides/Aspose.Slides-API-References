---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API Reference
description: Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only IPortionFormat.
type: docs
weight: 1
url: /cpp/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() method


Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Remarks


The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.

In order to get the effective values including inherited ones use the [PortionFormat::GetEffective](../../portionformat/geteffective/) method.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormat](../../iportionformat/)
* Class [Portion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
