---
title: Sequence
type: docs
weight: 0
url: /php-java/sequence/
---

# Sequence class

 Represents sequence (collection of effects).
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addEffect](/php-java/sequence/addeffect/)(IShape, int, int, int) | IEffect | Add new effect to the end of sequence. |
| [addEffect](/php-java/sequence/addeffect/)(IParagraph, int, int, int) | IEffect | Add new animation effect for paragraph to the end of sequence. |
| [addEffect](/php-java/sequence/addeffect/)(IChart, int, int, int, int, int) | IEffect | Adds the new chart animation effect for category or series to the end of sequence. |
| [addEffect](/php-java/sequence/addeffect/)(IChart, int, int, int, int, int, int) | IEffect | Adds the new chart animation effect for elements in category or series to the end of sequence. |
| [clear](/php-java/sequence/clear/)() | void | Removes all effects from a collection. |
| [getCount](/php-java/sequence/getcount/)() | int | Returns the number of effects in a sequense. Read-only int. |
| [getCount](/php-java/sequence/getcount/)(IShape) | int | Returns count of effects for the specified shape. |
| [getEffectsByParagraph](/php-java/sequence/geteffectsbyparagraph/)(IParagraph) | IEffect | Returns array of effects for the specified paragraph. |
| [getEffectsByShape](/php-java/sequence/geteffectsbyshape/)(IShape) | IEffect | Returns array of effects for the specified shape. |
| [getTriggerShape](/php-java/sequence/gettriggershape/)() | IShape | Returns or sets shape target for INTERACTIVE sequence. If sequence is not interactive then returns null. Read/write IShape. |
| [get_Item](/php-java/sequence/get_item/)(int) | IEffect | Returns an effect at the specified index. |
| [iterator](/php-java/sequence/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/sequence/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/php-java/sequence/remove/)(IEffect) | void | Removes specified effect from a collection. |
| [removeAt](/php-java/sequence/removeat/)(int) | void | Removes an effect from a collection. |
| [removeByShape](/php-java/sequence/removebyshape/)(IShape) | void | Remove effect for the specified shape. |
| [setTriggerShape](/php-java/sequence/settriggershape/)(IShape) | void | Returns or sets shape target for INTERACTIVE sequence. If sequence is not interactive then returns null. Read/write IShape. |
