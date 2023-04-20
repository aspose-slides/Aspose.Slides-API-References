---
title: get_Separator()
second_title: Aspose.Slides for C++ API Reference
description: "Sets or returns a Variant representing the separator used for the data labels on a chart. Read System::String."
type: docs
weight: 326
url: /cpp/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() method


Sets or returns a Variant representing the separator used for the data labels on a chart. Read [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## Remarks


If parent of this [DataLabelFormat](../) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the Separator property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" cause to all DataLabels[i].Separator is equal to val). 



## See Also

* Class [String](../../../system/string/)
* Class [DataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)