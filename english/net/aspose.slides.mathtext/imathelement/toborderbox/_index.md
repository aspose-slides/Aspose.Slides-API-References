---
title: ToBorderBox
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 190
url: /net/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement.ToBorderBox method (1 of 2)

Places this element in a border-box

```csharp
public IMathBorderBox ToBorderBox()
```

## Return Value

Border-box with this element placed inside

### Examples

Example:

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox();
```

### See Also

* interface [IMathBorderBox](../../imathborderbox)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.ToBorderBox method (2 of 2)

Places this element in a border-box

```csharp
public IMathBorderBox ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, 
    bool strikethroughHorizontal, bool strikethroughVertical, 
    bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | Boolean | Hide Top Edge |
| hideBottom | Boolean | Hide Bottom Edge |
| hideLeft | Boolean | Hide Left Edge |
| hideRight | Boolean | Hide Right Edge |
| strikethroughHorizontal | Boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | Boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | Boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | Boolean | Border Box Strikethrough Top-Left to Bottom-Right |

## Return Value

Border-box with this element placed inside

### Examples

Example:

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox(false, false, true, true, false, false, false, false);
```

### See Also

* interface [IMathBorderBox](../../imathborderbox)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
