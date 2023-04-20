---
title: set_ShowPercentage()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write bool.
type: docs
weight: 209
url: /cpp/aspose.slides.charts/idatalabelformat/set_showpercentage/
---
## IDataLabelFormat::set_ShowPercentage(bool) method


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowPercentage(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" cause to all DataLabels[i].ShowPercentage is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)