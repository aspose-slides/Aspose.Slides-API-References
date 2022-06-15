---
title: SectionCollection
type: docs
weight: 0
url: /php-java/sectioncollection/
---

# SectionCollection class

 Represents a collection of sections.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addEmptySection](/slides/php-java/sectioncollection/addemptysection/)(String, int) | ISection | Add empty section to specified position of the collection. |
| [addSection](/slides/php-java/sectioncollection/addsection/)(String, ISlide) | ISection | Add slides section started form specific slide. |
| [appendEmptySection](/slides/php-java/sectioncollection/appendemptysection/)(String) | ISection | Add empty section to the end of the collection. |
| [clear](/slides/php-java/sectioncollection/clear/)() | void | Removes all sections from the collection. |
| [getSyncRoot](/slides/php-java/sectioncollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/sectioncollection/get_item/)(int) | ISection | Gets the element at the specified index. Read-only ISection. |
| [indexOf](/slides/php-java/sectioncollection/indexof/)(ISection) | int | Returns an index of the specified section in the collection. |
| [isSynchronized](/slides/php-java/sectioncollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/sectioncollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/sectioncollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeSection](/slides/php-java/sectioncollection/removesection/)(ISection) | void | Remove section. Slides contained in the section will be merged into previous section. |
| [removeSectionWithSlides](/slides/php-java/sectioncollection/removesectionwithslides/)(ISection) | void | Remove section and slides contained in the section. |
| [reorderSectionWithSlides](/slides/php-java/sectioncollection/reordersectionwithslides/)(ISection, int) | void | Moves section and its slides from the collection to the specified position. |
| [size](/slides/php-java/sectioncollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
