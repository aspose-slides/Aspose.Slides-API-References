---
title: MathNaryOperator
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathnaryoperator/
---

## MathNaryOperator class

 Specifies an N-ary mathematical object, such as Summation and Integral.
 It consists of an operator, a base (or operand), and optional upper and lower limits. 
 Examples of N-ary operators are: Summation, Union, Intersection, Integral 
 
Example:
 
```php
  $naryOperator = new MathematicalText("x")->nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

## Constructors

| Name | Description |
| --- | --- |
| [MathNaryOperator](mathnaryoperator)(char, IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator](mathnaryoperator)(char, IMathElement, IMathElement) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator](mathnaryoperator)(char, IMathElement) | Initializes a new instance of the MathNaryOperator class. |

## Methods

| Name | Description |
| --- | --- |
| [getBase](getbase)() | Base argument |
| [getChildren](getchildren)() | Get children elements |
| [getGrowToMatchOperandHeight](getgrowtomatchoperandheight)() | Operator Character grows vertically to match its operand height |
| [getHideSubscript](gethidesubscript)() | Hide Subscript |
| [getHideSuperscript](gethidesuperscript)() | Hide Superscript |
| [getLimitLocation](getlimitlocation)() | The location of limits (subscript and superscript) |
| [getOperator](getoperator)() | Nary Operator Character For example: '?', '?' |
| [getSubscript](getsubscript)() | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript](getsuperscript)() | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
| [setGrowToMatchOperandHeight](setgrowtomatchoperandheight)(boolean) | Operator Character grows vertically to match its operand height |
| [setHideSubscript](sethidesubscript)(boolean) | Hide Subscript |
| [setHideSuperscript](sethidesuperscript)(boolean) | Hide Superscript |
| [setLimitLocation](setlimitlocation)(int) | The location of limits (subscript and superscript) |
| [setOperator](setoperator)(char) | Nary Operator Character For example: '?', '?' |
