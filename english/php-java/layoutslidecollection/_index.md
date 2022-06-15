---
title: LayoutSlideCollection
type: docs
weight: 0
url: /php-java/layoutslidecollection/
---

# LayoutSlideCollection class

 Represents a base class for collection of a layout slides.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getByType](/slides/php-java/layoutslidecollection/getbytype/)(byte) | ILayoutSlide | Returns the first layout slide of specified type. |
| [getSyncRoot](/slides/php-java/layoutslidecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/layoutslidecollection/get_item/)(int) | ILayoutSlide | Returns the layout slide by index. Read-only LayoutSlide. |
| [isSynchronized](/slides/php-java/layoutslidecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/layoutslidecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/layoutslidecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/layoutslidecollection/remove/)(ILayoutSlide) | void | Removes a layout from the collection. |
| [removeUnused](/slides/php-java/layoutslidecollection/removeunused/)() | void | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
| [size](/slides/php-java/layoutslidecollection/size/)() | int | Returns the number of layout slides in a collection. Read-only int. |
