---
title: MotionPath
type: docs
weight: 0
url: /php-java/motionpath/
---

# MotionPath class

 Represent motion path.
 

## Constructors

| name | description |
| --- | --- |
| [MotionPath](/slides/php-java/motionpath/motionpath/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/slides/php-java/motionpath/add/)(int, java.awt.geom.Point2D.Float[], int, boolean) | IMotionCmdPath | Add new command to path |
| [clear](/slides/php-java/motionpath/clear/)() | void | Removes all commands from the collection. |
| [getCount](/slides/php-java/motionpath/getcount/)() | int | Returns the number of paths in the collection. Read-only int. |
| [get_Item](/slides/php-java/motionpath/get_item/)(int) | IMotionCmdPath | Returns a command at the specified index. |
| [insert](/slides/php-java/motionpath/insert/)(int, int, java.awt.geom.Point2D.Float[], int, boolean) | void | Insert new command to path |
| [iterator](/slides/php-java/motionpath/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/motionpath/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/motionpath/remove/)(IMotionCmdPath) | void | Removes specified commans from the collection. |
| [removeAt](/slides/php-java/motionpath/removeat/)(int) | void | Removes a command at the specified index. |
