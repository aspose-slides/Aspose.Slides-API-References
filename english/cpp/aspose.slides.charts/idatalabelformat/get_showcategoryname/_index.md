---
title: get_ShowCategoryName()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read bool.
type: docs
weight: 144
url: /cpp/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() method


Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;\" cause to all DataLabels[i].ShowCategoryName is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)