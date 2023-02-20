---
title: BulletFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/bulletformat/
---

## BulletFormat class

 Represents paragraph bullet formatting properties.
 

## Methods

| Name | Description |
| --- | --- |
| [applyDefaultParagraphIndentsShifts](applydefaultparagraphindentsshifts)() | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |
| [getChar](getchar)() | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |
| [getColor](getcolor)() | Returns the color format of a bullet of a paragraph with no inheritance. Read-only IColorFormat. |
| [getEffective](geteffective)() | Gets effective bullet formatting data with the inheritance applied. |
| [getFont](getfont)() | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |
| [getHeight](getheight)() | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |
| [getNumberedBulletStartWith](getnumberedbulletstartwith)() | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |
| [getNumberedBulletStyle](getnumberedbulletstyle)() | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |
| [getPicture](getpicture)() | Returns the picture used as a bullet in a paragraph with no inheritance. Read-only ISlidesPicture. |
| [getType](gettype)() | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |
| [getVersion](getversion)() |  |
| [isBulletHardColor](isbullethardcolor)() | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |
| [isBulletHardFont](isbullethardfont)() | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |
| [setBulletHardColor](setbullethardcolor)(byte) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |
| [setBulletHardFont](setbullethardfont)(byte) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |
| [setChar](setchar)(char) | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |
| [setFont](setfont)([FontData](../fontdata)) | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |
| [setHeight](setheight)(float) | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |
| [setNumberedBulletStartWith](setnumberedbulletstartwith)(short) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |
| [setNumberedBulletStyle](setnumberedbulletstyle)(byte) | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |
| [setType](settype)(byte) | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |
