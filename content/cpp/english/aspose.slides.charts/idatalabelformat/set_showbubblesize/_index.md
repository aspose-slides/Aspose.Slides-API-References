---
title: set_ShowBubbleSize()
second_title: Aspose.Slides for C++ API Reference
description: Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Write bool.
type: docs
weight: 235
url: /aspose.slides.charts/idatalabelformat/set_showbubblesize/
---
## IDataLabelFormat::set_ShowBubbleSize(bool) method


Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowBubbleSize(bool value)=0
```

## Remarks


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;\" cause to all DataLabels[i].ShowBubbleSize is equal to val). 
## See Also

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)