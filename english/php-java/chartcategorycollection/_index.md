---
title: ChartCategoryCollection
type: docs
weight: 0
url: /php-java/chartcategorycollection/
---

# ChartCategoryCollection class

 Represents collection of  ChartCategory
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/slides/php-java/chartcategorycollection/add/)(IChartDataCell) | IChartCategory | If category exists in collection, return it. Else creates new chart category from IChartDataCell and adds it to the collection. |
| [add](/slides/php-java/chartcategorycollection/add/)(Object) | IChartCategory | Creates new ChartCategory from value and adds it to the collection. |
| [clear](/slides/php-java/chartcategorycollection/clear/)() | void | Removes all elements from the collection. |
| [getGroupingLevelCount](/slides/php-java/chartcategorycollection/getgroupinglevelcount/)() | int | Returns count of category grouping levels used. Is more then one for multilevel categories. Read-only int. |
| [getSyncRoot](/slides/php-java/chartcategorycollection/getsyncroot/)() | Object | Returns an object that can be used to synchronize access to the collection. Read-only Object. Returns a synchronization root. Read-only Object. |
| [getUseCells](/slides/php-java/chartcategorycollection/getusecells/)() | boolean | If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean. |
| [get_Item](/slides/php-java/chartcategorycollection/get_item/)(int) | IChartCategory | Gets the element at the specified index. |
| [indexOf](/slides/php-java/chartcategorycollection/indexof/)(IChartCategory) | int | Searches for the specified ChartCategory and returns the zero-based index of the first occurrence within the entire Collection. |
| [isSynchronized](/slides/php-java/chartcategorycollection/issynchronized/)() | boolean | Returns a value indicating whether access to the List is synchronized (thread safe). Read-only boolean. |
| [iterator](/slides/php-java/chartcategorycollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/chartcategorycollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/chartcategorycollection/remove/)(IChartCategory) | void | Removes the specified value. |
| [removeAt](/slides/php-java/chartcategorycollection/removeat/)(int) | void | Removes the element at the given index. |
| [setUseCells](/slides/php-java/chartcategorycollection/setusecells/)(boolean) | void | If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean. |
| [size](/slides/php-java/chartcategorycollection/size/)() | int | Returns a number of elements int the collection. Read-only int. |
