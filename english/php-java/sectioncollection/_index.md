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
| [addEmptySection](/php-java/sectioncollection/addemptysection/)(String, int) | ISection | Add empty section to specified position of the collection. |
| [addSection](/php-java/sectioncollection/addsection/)(String, ISlide) | ISection | Add slides section started form specific slide. |
| [appendEmptySection](/php-java/sectioncollection/appendemptysection/)(String) | ISection | Add empty section to the end of the collection. |
| [clear](/php-java/sectioncollection/clear/)() | void | Removes all sections from the collection. |
| [getSyncRoot](/php-java/sectioncollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/sectioncollection/get_item/)(int) | ISection | Gets the element at the specified index. Read-only ISection. |
| [indexOf](/php-java/sectioncollection/indexof/)(ISection) | int | Returns an index of the specified section in the collection. |
| [isSynchronized](/php-java/sectioncollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/sectioncollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/sectioncollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeSection](/php-java/sectioncollection/removesection/)(ISection) | void | Remove section. Slides contained in the section will be merged into previous section. |
| [removeSectionWithSlides](/php-java/sectioncollection/removesectionwithslides/)(ISection) | void | Remove section and slides contained in the section. |
| [reorderSectionWithSlides](/php-java/sectioncollection/reordersectionwithslides/)(ISection, int) | void | Moves section and its slides from the collection to the specified position. |
| [size](/php-java/sectioncollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
