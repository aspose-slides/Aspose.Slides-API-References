---
title: get_ShowSeriesName()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read bool.
type: docs
weight: 170
url: /cpp/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() method


Returns a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" cause to all DataLabels[i].ShowSeriesName is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
