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
| [MotionPath](/php-java/motionpath/motionpath/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/php-java/motionpath/add/)(int, java.awt.geom.Point2D.Float[], int, boolean) | IMotionCmdPath | Add new command to path |
| [clear](/php-java/motionpath/clear/)() | void | Removes all commands from the collection. |
| [getCount](/php-java/motionpath/getcount/)() | int | Returns the number of paths in the collection. Read-only int. |
| [get_Item](/php-java/motionpath/get_item/)(int) | IMotionCmdPath | Returns a command at the specified index. |
| [insert](/php-java/motionpath/insert/)(int, int, java.awt.geom.Point2D.Float[], int, boolean) | void | Insert new command to path |
| [iterator](/php-java/motionpath/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/motionpath/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/php-java/motionpath/remove/)(IMotionCmdPath) | void | Removes specified commans from the collection. |
| [removeAt](/php-java/motionpath/removeat/)(int) | void | Removes a command at the specified index. |
