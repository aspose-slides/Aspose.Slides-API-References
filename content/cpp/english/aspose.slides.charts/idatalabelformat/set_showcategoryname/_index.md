---
title: set_ShowCategoryName()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Write bool.
type: docs
weight: 157
url: /aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) method


Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;\" cause to all DataLabels[i].ShowCategoryName is equal to val). 



## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)