---
title: MathBox
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/mathbox/
---

## MathBox class

 Specifies the logical boxing (packaging) of mathematical element.
 For example, a boxed object can serve as an operator emulator with or without an alignment point, 
 serve as a line break point, or be grouped such as not to allow line breaks within.
 For example, the "==" operator should be boxed to prevent line breaks.
 

## Functions

| Name | Description |
| --- | --- |
| [MathBox](mathbox)([MathLimit](../mathlimit)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathBorderBox](../mathborderbox)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathFraction](../mathfraction)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathDelimiter](../mathdelimiter)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathSuperscriptElement](../mathsuperscriptelement)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathBox](../mathbox)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathMatrix](../mathmatrix)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathGroupingCharacter](../mathgroupingcharacter)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathArray](../matharray)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathBlock](../mathblock)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathSubscriptElement](../mathsubscriptelement)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathFunction](../mathfunction)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathNaryOperator](../mathnaryoperator)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathematicalText](../mathematicaltext)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathAccent](../mathaccent)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathRadical](../mathradical)) | Initializes MathBox with the specified element as an argument |
| [MathBox](mathbox)([MathBar](../mathbar)) | Initializes MathBox with the specified element as an argument |

## Functions

| Name | Description |
| --- | --- |
| [getAlignmentPoint](getalignmentpoint)() | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false |
| [getBase](getbase)() | Base argument |
| [getChildren](getchildren)() | Get children elements |
| [getDifferential](getdifferential)() | Differential When true, the box acts as a differential (e.g., ?? in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false |
| [getExplicitBreak](getexplicitbreak)() | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break) |
| [getNoBreak](getnobreak)() | No break This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true |
| [getOperatorEmulator](getoperatoremulator)() | Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false |
| [setAlignmentPoint](setalignmentpoint)(boolean) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false |
| [setDifferential](setdifferential)(boolean) | Differential When true, the box acts as a differential (e.g., ?? in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false |
| [setExplicitBreak](setexplicitbreak)(byte) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break) |
| [setNoBreak](setnobreak)(boolean) | No break This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true |
| [setOperatorEmulator](setoperatoremulator)(boolean) | Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false |
