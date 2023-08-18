---
title: get_Position()
second_title: Aspose.Slides for C++ API Reference
description: Represents the position of the data label. Read LegendDataLabelPosition.
type: docs
weight: 66
url: /aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() method


Represents the position of the data label. Read [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Represents the position for the [DataLabel](../../datalabel/) objects. Set this property with value also sets this value to the Position property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.Position = val;\" cause to all DataLabels[i].Position is equal to val). 



## See Also

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)