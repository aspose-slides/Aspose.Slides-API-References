---
title: MathNaryOperator
type: docs
weight: 0
url: /php-java/mathnaryoperator/
---

# MathNaryOperator class

 Specifies an N-ary mathematical object, such as Summation and Integral.
 It consists of an operator, a base (or operand), and optional upper and lower limits. 
 Examples of N-ary operators are: Summation, Union, Intersection, Integral 
 
Example:
 
```php
  $naryOperator = new MathematicalText("x")->nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

## Constructors

| name | description |
| --- | --- |
| [MathNaryOperator](/php-java/mathnaryoperator/mathnaryoperator/)(char, IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator](/php-java/mathnaryoperator/mathnaryoperator/)(char, IMathElement, IMathElement) | Initializes a new instance of the MathNaryOperator class. |
| [MathNaryOperator](/php-java/mathnaryoperator/mathnaryoperator/)(char, IMathElement) | Initializes a new instance of the MathNaryOperator class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/php-java/mathnaryoperator/getbase/)() | IMathElement | Base argument |
| [getChildren](/php-java/mathnaryoperator/getchildren/)() | IMathElement | Get children elements |
| [getGrowToMatchOperandHeight](/php-java/mathnaryoperator/getgrowtomatchoperandheight/)() | boolean | Operator Character grows vertically to match its operand height |
| [getHideSubscript](/php-java/mathnaryoperator/gethidesubscript/)() | boolean | Hide Subscript |
| [getHideSuperscript](/php-java/mathnaryoperator/gethidesuperscript/)() | boolean | Hide Superscript |
| [getLimitLocation](/php-java/mathnaryoperator/getlimitlocation/)() | int | The location of limits (subscript and superscript) |
| [getOperator](/php-java/mathnaryoperator/getoperator/)() | char | Nary Operator Character For example: '?', '?' |
| [getSubscript](/php-java/mathnaryoperator/getsubscript/)() | IMathElement | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript](/php-java/mathnaryoperator/getsuperscript/)() | IMathElement | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
| [setGrowToMatchOperandHeight](/php-java/mathnaryoperator/setgrowtomatchoperandheight/)(boolean) | void | Operator Character grows vertically to match its operand height |
| [setHideSubscript](/php-java/mathnaryoperator/sethidesubscript/)(boolean) | void | Hide Subscript |
| [setHideSuperscript](/php-java/mathnaryoperator/sethidesuperscript/)(boolean) | void | Hide Superscript |
| [setLimitLocation](/php-java/mathnaryoperator/setlimitlocation/)(int) | void | The location of limits (subscript and superscript) |
| [setOperator](/php-java/mathnaryoperator/setoperator/)(char) | void | Nary Operator Character For example: '?', '?' |
