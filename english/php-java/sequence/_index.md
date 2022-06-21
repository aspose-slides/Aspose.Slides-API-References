---
title: Sequence
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/sequence/
---

## Sequence class

 Represents sequence (collection of effects).
 

## Methods

| Name | Description |
| --- | --- |
| [addEffect](addeffect)(IShape, int, int, int) | Add new effect to the end of sequence. |
| [addEffect](addeffect)(IParagraph, int, int, int) | Add new animation effect for paragraph to the end of sequence. |
| [addEffect](addeffect)(IChart, int, int, int, int, int) | Adds the new chart animation effect for category or series to the end of sequence. |
| [addEffect](addeffect)(IChart, int, int, int, int, int, int) | Adds the new chart animation effect for elements in category or series to the end of sequence. |
| [clear](clear)() | Removes all effects from a collection. |
| [getCount](getcount)() | Returns the number of effects in a sequense. Read-only int. |
| [getCount](getcount)(IShape) | Returns count of effects for the specified shape. |
| [getEffectsByParagraph](geteffectsbyparagraph)(IParagraph) | Returns array of effects for the specified paragraph. |
| [getEffectsByShape](geteffectsbyshape)(IShape) | Returns array of effects for the specified shape. |
| [getTriggerShape](gettriggershape)() | Returns or sets shape target for INTERACTIVE sequence. If sequence is not interactive then returns null. Read/write IShape. |
| [get_Item](get_item)(int) | Returns an effect at the specified index. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [remove](remove)(IEffect) | Removes specified effect from a collection. |
| [removeAt](removeat)(int) | Removes an effect from a collection. |
| [removeByShape](removebyshape)(IShape) | Remove effect for the specified shape. |
| [setTriggerShape](settriggershape)(IShape) | Returns or sets shape target for INTERACTIVE sequence. If sequence is not interactive then returns null. Read/write IShape. |
