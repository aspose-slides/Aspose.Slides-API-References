---
title: MasterLayoutSlideCollection
type: docs
weight: 0
url: /php-java/masterlayoutslidecollection/
---

# MasterLayoutSlideCollection class

 Represents a collections of all layout slides of defined master slide.
 Extends LayoutSlideCollection class with methods for adding/inserting/removing/cloning/reordering 
 layout slides in context of the individual collections of master's layout slides.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/slides/php-java/masterlayoutslidecollection/add/)(byte, String) | ILayoutSlide | Adds a new layout slide to the end of the collection. |
| [addClone](/slides/php-java/masterlayoutslidecollection/addclone/)(ILayoutSlide) | ILayoutSlide | Adds a copy of a specified layout slide to the end of the collection. |
| [insert](/slides/php-java/masterlayoutslidecollection/insert/)(int, byte, String) | ILayoutSlide | Inserts a new layout slide to specified position of the collection. |
| [insertClone](/slides/php-java/masterlayoutslidecollection/insertclone/)(int, ILayoutSlide) | ILayoutSlide | Inserts a copy of a specified layout slide to specified position of the collection. |
| [removeAt](/slides/php-java/masterlayoutslidecollection/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [reorder](/slides/php-java/masterlayoutslidecollection/reorder/)(int, ILayoutSlide) | void | Moves layout slide from the collection to the specified position. |
