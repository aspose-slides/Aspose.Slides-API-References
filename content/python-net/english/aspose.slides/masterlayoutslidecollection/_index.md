---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterlayoutslidecollection/
---


## MasterLayoutSlideCollection class

Represents a collections of all layout slides of defined master slide.
            Extends LayoutSlideCollection class with methods for adding/inserting/removing/cloning/reordering 
            layout slides in context of the individual collections of master's layout slides.

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/aspose.slides/layoutslidecollection)

The MasterLayoutSlideCollection type exposes the following members:

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_by_type`](/slides/python-net/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Returns the first layout slide of specified type.<br/>            A type of layout slide to find.[`LayoutSlide`](/slides/python-net/aspose.slides/layoutslide) with specified type or null if no layouts found. |
| [`remove`](/slides/python-net/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Removes a layout from the collection. |
| [`remove_unused`](/slides/python-net/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
| [`add_clone`](/slides/python-net/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Adds a copy of a specified layout slide to the end of the collection. |
| [`insert_clone`](/slides/python-net/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Inserts a copy of a specified layout slide to specified position of the collection. |
| [`add`](/slides/python-net/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Adds a new layout slide to the end of the collection. |
| [`insert`](/slides/python-net/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Inserts a new layout slide to specified position of the collection. |
| [`remove_at`](/slides/python-net/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Removes the element at the specified index of the collection. |
| [`reorder`](/slides/python-net/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Moves layout slide from the collection to the specified position. |


### See Also
* class [`LayoutSlideCollection`](/slides/python-net/aspose.slides/layoutslidecollection)
* class [`MasterLayoutSlideCollection`](/slides/python-net/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

