---
title: setNumberFormat
type: docs
weight: 170
url: /php-java/datalabelformat/setnumberformat/
---

# setNumberFormat(java.lang.String) method

 Represents the format string for the DataLabels object.
 Read/write  String.
 
 If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
 property gets or sets the default value of the NumberFormat property for the new data 
 labels in the DataLabelCollection collection.
 Represents the format string for the DataLabel objects.
 Set this property with value also sets this value to the NumberFormat property 
 for all data labels in the DataLabelCollection collection
 (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" cause to 
 all DataLabels.get_Item(i).getNumberFormat() is equal to val).
 

##  Returns
String

