---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API Reference
description: Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only IPortionFormat.
type: docs
weight: 1
url: /aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() method


Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Remarks


The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.

In order to get the effective values including inherited ones use [IPortionFormat::GetEffective](../../iportionformat/geteffective/) method.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormat](../../iportionformat/)
* Class [IPortion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)