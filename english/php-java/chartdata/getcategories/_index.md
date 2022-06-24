---
title: getCategories
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartdata/getcategories/
---

## getCategories() method

 Gets the primary categories (or both primary and secondary categories 
 if  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false).
 Read-only  IChartCategoryCollection.
 
 If  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then ( #getSecondaryCategories)
 property return null and data in this  #getCategories property is used both for primary 
 and secondary series.
 If  #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in ( #getSecondaryCategories)
 property is used for secondary series and data in this  #getCategories property is used 
 for primary series.
 

 Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
 
```php
  // related categories are series.getChart().getChartData().getSecondaryCategories()
  // related categories are series.getChart().getChartData().getCategories()
```

### Returns
#getCategories


---


