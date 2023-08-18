---
title: set_ShowValue()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write bool.
type: docs
weight: 131
url: /aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) method


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowValue property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" cause to all DataLabels[i].ShowValue is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)