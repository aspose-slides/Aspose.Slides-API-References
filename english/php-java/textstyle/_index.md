---
title: TextStyle
type: docs
weight: 0
url: /php-java/textstyle/
---

# TextStyle class

 This class contains the text style formatting properties.
 

## Constants

| name | description |
| --- | --- |
| MaxLevelCount | Maximum count of style levels that can be defined. Use it with #getLevel(int) for (int i = 0; i &lt; TextStyle.MaxLevelCount; i++) { IParagraphFormat paragraphFormat = getLevel(i); ... } |


## Methods

| name | return type | description |
| --- | --- | --- |
| [getDefaultParagraphFormat](/slides/php-java/textstyle/getdefaultparagraphformat/)() | IParagraphFormat | Default paragraph propertiies. Read-only IParagraphFormat. |
| [getEffective](/slides/php-java/textstyle/geteffective/)() | ITextStyleEffectiveData | Gets effective text style formatting data with the inheritance applied. |
| [getLevel](/slides/php-java/textstyle/getlevel/)(int) | IParagraphFormat | If level of style exist returns it, otherwise returns null. |
