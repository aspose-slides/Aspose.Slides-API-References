---
title: set_ShowLeaderLines()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Write bool.
type: docs
weight: 261
url: /aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) method


Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" cause to all DataLabels[i].ShowLeaderLines is equal to val). 
## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)