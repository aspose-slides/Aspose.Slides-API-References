---
title: Radical
second_title: Aspose.Sildes for .NET API Reference
description: Specifies the mathematical root of the given degree from the specified argument.
type: docs
weight: 110
url: /aspose.slides.mathtext/mathelementbase/radical/
---

## Radical(IMathElement) {#radical}

Specifies the mathematical root of the given degree from the specified argument.

```csharp
public IMathRadical Radical(IMathElement degree)
```

| Parameter | Type | Description |
| --- | --- | --- |
| degree | IMathElement | Argument of Radical |

### Return Value

New instance of type [`IMathRadical`](../../imathradical)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("2px");
IMathElement degree = new MathematicalText("y");
var radical = baseElement.Radical(degree);
```

### See Also

* interface [IMathRadical](../../imathradical)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Radical(string) {#radical_1}

Specifies the mathematical root of the given degree from the specified argument.

```csharp
public IMathRadical Radical(string degree)
```

| Parameter | Type | Description |
| --- | --- | --- |
| degree | String | Argument of Radical |

### Return Value

New instance of type [`IMathRadical`](../../imathradical)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("2px");
var radical = baseElement.Radical("3");
```

### See Also

* interface [IMathRadical](../../imathradical)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
