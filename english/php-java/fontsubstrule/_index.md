---
title: FontSubstRule
type: docs
weight: 0
url: /php-java/fontsubstrule/
---

# FontSubstRule class

 Represents font subtituition information
 

## Constructors

| name | description |
| --- | --- |
| [FontSubstRule](/php-java/fontsubstrule/fontsubstrule/)(IFontData, IFontData) | Creates new instance. |
| [FontSubstRule](/php-java/fontsubstrule/fontsubstrule/)(IFontData, IFontData, int) | Creates new instance. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDestFont](/php-java/fontsubstrule/getdestfont/)() | IFontData | Font to use for substitution. Read-only IFontData. |
| [getReplaceFontCondition](/php-java/fontsubstrule/getreplacefontcondition/)() | int | Rule to apply for substitution. Read-only FontSubstCondition. |
| [getSourceFont](/php-java/fontsubstrule/getsourcefont/)() | IFontData | Font to substitute. Read-only IFontData. |