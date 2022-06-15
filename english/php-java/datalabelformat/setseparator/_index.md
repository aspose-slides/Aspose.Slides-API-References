---
title: setSeparator
type: docs
weight: 200
url: /php-java/datalabelformat/setseparator/
---

# setSeparator(java.lang.String) method

 Sets or returns a Variant representing the separator used for the data labels on a chart.
 Read/write  String.
 
 If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
 property gets or sets the default value of the Separator property for the new data 
 labels in the DataLabelCollection collection.
 Set this property with value also sets this value to the Separator property 
 for all data labels in the DataLabelCollection collection
 (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to 
 all DataLabels.get_Item(i).getSeparator() is equal to val).
 

##  Returns
String


