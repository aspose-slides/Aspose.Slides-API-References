---
title: set_ShowSeriesName()
second_title: Aspose.Slides for C++ API Reference
description: Sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Write bool.
type: docs
weight: 183
url: /cpp/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) method


Sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" cause to all DataLabels[i].ShowSeriesName is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)