---
title: TextStyle
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/textstyle/
---

## TextStyle class

 This class contains the text style formatting properties.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| MaxLevelCount | 9 | Maximum count of style levels that can be defined. Use it with #getLevel(int) for (int i = 0; i &lt; TextStyle.MaxLevelCount; i++) { IParagraphFormat paragraphFormat = getLevel(i); ... } |


## Methods

| Name | Description |
| --- | --- |
| [getDefaultParagraphFormat](getdefaultparagraphformat)() | Default paragraph propertiies. Read-only IParagraphFormat. |
| [getEffective](geteffective)() | Gets effective text style formatting data with the inheritance applied. |
| [getLevel](getlevel)(int) | If level of style exist returns it, otherwise returns null. |
