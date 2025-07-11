---
title: IMathNaryOperator
second_title: Aspose.Sildes for .NET API Reference
description: Specifies an N-ary mathematical object such as Summation and Integral. It consists of an operator a base or operand and optional upper and lower limits. Examples of N-ary operators are Summation Union Intersection Integral
type: docs
weight: 8180
url: /aspose.slides.mathtext/imathnaryoperator/
---

## IMathNaryOperator interface

Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral

```csharp
public interface IMathNaryOperator : IMathElement, IMathNaryOperatorProperties
```

## Properties

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathnaryoperator/asimathelement) { get; } | Allows to get base IMathElement interface [`IMathElement`](../imathelement) |
| [AsIMathNaryOperatorProperties](../../aspose.slides.mathtext/imathnaryoperator/asimathnaryoperatorproperties) { get; } | Allows to get base IMathNaryOperatorProperties interface [`IMathNaryOperatorProperties`](../imathnaryoperatorproperties) |
| [Base](../../aspose.slides.mathtext/imathnaryoperator/base) { get; } | Base argument |
| [Subscript](../../aspose.slides.mathtext/imathnaryoperator/subscript) { get; } | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [Superscript](../../aspose.slides.mathtext/imathnaryoperator/superscript) { get; } | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |

### Examples

Example:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### See Also

* interface [IMathElement](../imathelement)
* interface [IMathNaryOperatorProperties](../imathnaryoperatorproperties)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
