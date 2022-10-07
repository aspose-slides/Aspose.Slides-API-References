---
title: getNumberFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/datalabelformat/getnumberformat/
---

## getNumberFormat()  method

 Represents the format string for the DataLabels object.
 Read/write  String.
 
 If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
 property gets or sets the default value of the NumberFormat property for the new data 
 labels in the DataLabelCollection collection.
 When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection
 (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).
 

 
```php
  $series->getLabels()->getDefaultDataLabelFormat()->setShowValue(true);
  $series->getLabels()->getDefaultDataLabelFormat()->setNumberFormatLinkedToSource(false);
  $series->getLabels()->getDefaultDataLabelFormat()->setNumberFormat("0.0%");
```

### Returns
String


---


