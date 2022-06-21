---
title: SectionCollection
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/sectioncollection/
---

## SectionCollection class

 Represents a collection of sections.
 

## Methods

| Name | Description |
| --- | --- |
| [addEmptySection](addemptysection)(String, int) | Add empty section to specified position of the collection. |
| [addSection](addsection)(String, ISlide) | Add slides section started form specific slide. |
| [appendEmptySection](appendemptysection)(String) | Add empty section to the end of the collection. |
| [clear](clear)() | Removes all sections from the collection. |
| [getSyncRoot](getsyncroot)() | Returns a synchronization root. Read-only Object. |
| [get_Item](get_item)(int) | Gets the element at the specified index. Read-only ISection. |
| [indexOf](indexof)(ISection) | Returns an index of the specified section in the collection. |
| [isSynchronized](issynchronized)() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [removeSection](removesection)(ISection) | Remove section. Slides contained in the section will be merged into previous section. |
| [removeSectionWithSlides](removesectionwithslides)(ISection) | Remove section and slides contained in the section. |
| [reorderSectionWithSlides](reordersectionwithslides)(ISection, int) | Moves section and its slides from the collection to the specified position. |
| [size](size)() | Gets the number of elements actually contained in the collection. Read-only int. |
