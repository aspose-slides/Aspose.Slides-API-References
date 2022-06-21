---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathrightsubsuperscriptelement/
---

## MathRightSubSuperscriptElement class

 Specifies the Sub-Superscript object, which consists of a base 
 and a subscript and superscript placed to the right of the base.
 
Example:
 
```php
  $subsuperscript = new MathematicalText("N")->SetSubSuperscriptOnTheRight("i", "j");
```

## Constructors

| Name | Description |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathRightSubSuperscriptElement class. |

## Methods

| Name | Description |
| --- | --- |
| [getAlignScripts](getalignscripts)() | Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false. |
| [getChildren](getchildren)() | Get children elements |
| [getSubscript](getsubscript)() | Subscript argument |
| [getSuperscript](getsuperscript)() | Superscript argument |
| [setAlignScripts](setalignscripts)(boolean) | Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false. |
