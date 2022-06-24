---
title: getUseSecondaryCategories
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 90
url: /php-java/chartdata/getusesecondarycategories/
---

## getUseSecondaryCategories() method

 If false then  #getSecondaryCategories property return null and data 
 in  #getCategories property is used both for primary and secondary series.
 If true then data in  #getSecondaryCategories property is used for secondary series and data 
 in  #getCategories property is used for primary series.
  
 Read/write  boolean.
 

 Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
 
```php
  // related categories are series.getChart().getChartData().getSecondaryCategories()
  // related categories are series.getChart().getChartData().getCategories()
```

### Returns
boolean


---


