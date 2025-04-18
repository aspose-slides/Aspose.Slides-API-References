---
title: SetLowerLimit
second_title: Aspose.Sildes for .NET API Reference
description: Takes lower limit
type: docs
weight: 120
url: /aspose.slides.mathtext/mathelementbase/setlowerlimit/
---

## SetLowerLimit(IMathElement) {#setlowerlimit}

Takes lower limit

```csharp
public IMathLimit SetLowerLimit(IMathElement limit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| limit | IMathElement | limit |

### Return Value

New instance of type [`IMathLimit`](../../imathlimit)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
IMathElement limitValue = new MathematicalText("𝑛→∞");
var limitElement = baseElement.SetLowerLimit(limitValue);
```

### See Also

* interface [IMathLimit](../../imathlimit)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## SetLowerLimit(string) {#setlowerlimit_1}

Takes lower limit

```csharp
public IMathLimit SetLowerLimit(string limit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| limit | String | limit |

### Return Value

New instance of type [`IMathLimit`](../../imathlimit)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
var limitElement = baseElement.SetLowerLimit("𝑛→∞");
```

### See Also

* interface [IMathLimit](../../imathlimit)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
