---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API Reference
description: "Represents the format string for the DataLabels object. Read System::String."
type: docs
weight: 27
url: /cpp/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() method


Represents the format string for the DataLabels object. Read [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Remarks



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" causes all DataLabels[i].NumberFormat to equal to val). 
## See Also

* Class [String](../../../system/string/)
* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
