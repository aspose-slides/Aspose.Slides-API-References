---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Write bool.
type: docs
weight: 313
url: /cpp/aspose.slides.charts/idatalabelformat/set_showlabelvaluefromcell/
---
## IDataLabelFormat::set_ShowLabelValueFromCell(bool) method


Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelValueFromCell(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" cause to all DataLabels[i].ShowLabelValueFromCell is equal to val). 
## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)