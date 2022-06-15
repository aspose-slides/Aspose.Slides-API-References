---
title: MathBox
type: docs
weight: 0
url: /php-java/mathbox/
---

# MathBox class

 Specifies the logical boxing (packaging) of mathematical element.
 For example, a boxed object can serve as an operator emulator with or without an alignment point, 
 serve as a line break point, or be grouped such as not to allow line breaks within.
 For example, the "==" operator should be boxed to prevent line breaks.
 
Example:
 
```php
  $box = new MathBox(new MathematicalText("=="));
```

## Constructors

| name | description |
| --- | --- |
| [MathBox](/php-java/mathbox/mathbox/)(IMathElement) | Initializes MathBox with the specified element as an argument |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAlignmentPoint](/php-java/mathbox/getalignmentpoint/)() | boolean | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false |
| [getBase](/php-java/mathbox/getbase/)() | IMathElement | Base argument |
| [getChildren](/php-java/mathbox/getchildren/)() | IMathElement | Get children elements |
| [getDifferential](/php-java/mathbox/getdifferential/)() | boolean | Differential When true, the box acts as a differential (e.g., ?? in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false |
| [getExplicitBreak](/php-java/mathbox/getexplicitbreak/)() | byte | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break) |
| [getNoBreak](/php-java/mathbox/getnobreak/)() | boolean | No break This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true |
| [getOperatorEmulator](/php-java/mathbox/getoperatoremulator/)() | boolean | Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false |
| [setAlignmentPoint](/php-java/mathbox/setalignmentpoint/)(boolean) | void | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false |
| [setDifferential](/php-java/mathbox/setdifferential/)(boolean) | void | Differential When true, the box acts as a differential (e.g., ?? in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false |
| [setExplicitBreak](/php-java/mathbox/setexplicitbreak/)(byte) | void | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break) |
| [setNoBreak](/php-java/mathbox/setnobreak/)(boolean) | void | No break This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true |
| [setOperatorEmulator](/php-java/mathbox/setoperatoremulator/)(boolean) | void | Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false |
