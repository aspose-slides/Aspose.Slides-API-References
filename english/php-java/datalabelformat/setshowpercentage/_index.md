---
title: setShowPercentage
type: docs
weight: 270
url: /php-java/datalabelformat/setshowpercentage/
---

# setShowPercentage(boolean) method

 Represents a specified chart's data label percentage value display behavior. 
 True displays the percentage value. False to hide.
 Read/write  boolean.
 
 If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
 property gets or sets the default value of the ShowPercentage property for the new data 
 labels in the DataLabelCollection collection.
 Set this property with value also sets this value to the ShowPercentage property 
 for all data labels in the DataLabelCollection collection
 (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to 
 all DataLabels.get_Item(i).getShowPercentage() is equal to val).
 

##  Returns
boolean

