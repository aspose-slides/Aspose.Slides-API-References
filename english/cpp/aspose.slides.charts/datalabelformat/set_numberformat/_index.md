---
title: set_NumberFormat()
second_title: Aspose.Slides for C++ API Reference
description: "Represents the format string for the DataLabels object. Write System::String."
type: docs
weight: 40
url: /cpp/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat([System::String](../../../system/string/)) method


Represents the format string for the DataLabels object. Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Remarks



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





If parent of this [DataLabelFormat](../) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" causes all DataLabels[i].NumberFormat to equal to val). 



## See Also

* Class [String](../../../system/string/)
* Class [DataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
