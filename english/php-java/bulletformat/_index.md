---
title: BulletFormat
type: docs
weight: 0
url: /php-java/bulletformat/
---

# BulletFormat class

 Represents paragraph bullet formatting properties.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [applyDefaultParagraphIndentsShifts](/php-java/bulletformat/applydefaultparagraphindentsshifts/)() | void | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |
| [getChar](/php-java/bulletformat/getchar/)() | char | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |
| [getColor](/php-java/bulletformat/getcolor/)() | IColorFormat | Returns the color format of a bullet of a paragraph with no inheritance. Read-only IColorFormat. |
| [getEffective](/php-java/bulletformat/geteffective/)() | IBulletFormatEffectiveData | Gets effective bullet formatting data with the inheritance applied. |
| [getFont](/php-java/bulletformat/getfont/)() | IFontData | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |
| [getHeight](/php-java/bulletformat/getheight/)() | float | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |
| [getNumberedBulletStartWith](/php-java/bulletformat/getnumberedbulletstartwith/)() | short | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |
| [getNumberedBulletStyle](/php-java/bulletformat/getnumberedbulletstyle/)() | byte | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |
| [getPicture](/php-java/bulletformat/getpicture/)() | ISlidesPicture | Returns the picture used as a bullet in a paragraph with no inheritance. Read-only ISlidesPicture. |
| [getType](/php-java/bulletformat/gettype/)() | byte | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |
| [getVersion](/php-java/bulletformat/getversion/)() | long |  |
| [isBulletHardColor](/php-java/bulletformat/isbullethardcolor/)() | byte | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool#True if bullet has own color and NullableBool#False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |
| [isBulletHardFont](/php-java/bulletformat/isbullethardfont/)() | byte | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool#True if bullet has own font and NullableBool#False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |
| [setBulletHardColor](/php-java/bulletformat/setbullethardcolor/)(byte) | void | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool#True if bullet has own color and NullableBool#False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |
| [setBulletHardFont](/php-java/bulletformat/setbullethardfont/)(byte) | void | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool#True if bullet has own font and NullableBool#False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |
| [setChar](/php-java/bulletformat/setchar/)(char) | void | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |
| [setFont](/php-java/bulletformat/setfont/)(IFontData) | void | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |
| [setHeight](/php-java/bulletformat/setheight/)(float) | void | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |
| [setNumberedBulletStartWith](/php-java/bulletformat/setnumberedbulletstartwith/)(short) | void | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |
| [setNumberedBulletStyle](/php-java/bulletformat/setnumberedbulletstyle/)(byte) | void | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |
| [setType](/php-java/bulletformat/settype/)(byte) | void | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |
