---
title: set_Separator()
second_title: Aspose.Slides for C++ API Reference
description: "Sets or returns a Variant representing the separator used for the data labels on a chart. Write System::String."
type: docs
weight: 339
url: /aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) method


Sets or returns a Variant representing the separator used for the data labels on a chart. Write [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the Separator property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" cause to all DataLabels[i].Separator is equal to val). 



## See Also

* Class [String](../../../system/string/)
* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)