---
title: SetSubscript
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 130
url: /net/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase.SetSubscript method (1 of 2)

Creates subscript

```csharp
public IMathSubscriptElement SetSubscript(IMathElement subscript)
```

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | IMathElement | Subscript (lower index on the right) |

## Return Value

New math element of type [`IMathSubscriptElement`](../../imathsubscriptelement)

### Examples

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathElement index = new MathematicalText("i");
IMathSubscriptElement subscript = element.SetSubscript(index);
```

### See Also

* interface [IMathSubscriptElement](../../imathsubscriptelement)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## MathElementBase.SetSubscript method (2 of 2)

Creates subscript

```csharp
public IMathSubscriptElement SetSubscript(string subscript)
```

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | String | Subscript (lower index on the right) |

## Return Value

New math element of type [`IMathSubscriptElement`](../../imathsubscriptelement)

### Examples

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("N");
IMathSubscriptElement subscript = element.SetSubscript("i");
```

### See Also

* interface [IMathSubscriptElement](../../imathsubscriptelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
