---
title: MathRightSubSuperscriptElement
type: docs
weight: 0
url: /php-java/mathrightsubsuperscriptelement/
---

# MathRightSubSuperscriptElement class

 Specifies the Sub-Superscript object, which consists of a base 
 and a subscript and superscript placed to the right of the base.
 
Example:
 
```php
  $subsuperscript = new MathematicalText("N")->SetSubSuperscriptOnTheRight("i", "j");
```

## Constructors

| name | description |
| --- | --- |
| [MathRightSubSuperscriptElement](/php-java/mathrightsubsuperscriptelement/mathrightsubsuperscriptelement/)(IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathRightSubSuperscriptElement class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAlignScripts](/php-java/mathrightsubsuperscriptelement/getalignscripts/)() | boolean | Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false. |
| [getChildren](/php-java/mathrightsubsuperscriptelement/getchildren/)() | IMathElement | Get children elements |
| [getSubscript](/php-java/mathrightsubsuperscriptelement/getsubscript/)() | IMathElement | Subscript argument |
| [getSuperscript](/php-java/mathrightsubsuperscriptelement/getsuperscript/)() | IMathElement | Superscript argument |
| [setAlignScripts](/php-java/mathrightsubsuperscriptelement/setalignscripts/)(boolean) | void | Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false. |