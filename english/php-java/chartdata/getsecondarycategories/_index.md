---
title: getSecondaryCategories
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/chartdata/getsecondarycategories/
---

## getSecondaryCategories()  method

 Gets the secondary categories if  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true.
 Read-only  IChartCategoryCollection.
 
 If  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then this ( #getSecondaryCategories)
 property return null and data in  #getCategories property is used both for primary 
 and secondary series.
 If  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in 
 this  #getSecondaryCategories property is used for secondary series and data 
 in  #getCategories property is used for primary series.
  
 

 Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
 
```php
  // related categories are series.getChart().getChartData().getSecondaryCategories()
  // related categories are series.getChart().getChartData().getCategories()
```

### Returns
[ChartCategoryCollection](../../chartcategorycollection)


---


