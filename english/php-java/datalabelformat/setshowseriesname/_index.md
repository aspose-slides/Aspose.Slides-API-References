---
title: setShowSeriesName
type: docs
weight: 280
url: /php-java/datalabelformat/setshowseriesname/
---

# setShowSeriesName(boolean) method

 Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
 True to show the series name. False to hide.
 Read/write  boolean.
 
 If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
 property gets or sets the default value of the ShowSeriesName property for the new data 
 labels in the DataLabelCollection collection.
 Set this property with value also sets this value to the ShowSeriesName property 
 for all data labels in the DataLabelCollection collection
 (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to 
 all DataLabels.get_Item(i).getShowSeriesName() is equal to val).
 

##  Returns
boolean

