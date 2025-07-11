---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Sildes for .NET API Reference
description: Controls SVG shape and text generation.
type: docs
weight: 4010
url: /aspose.slides.export/isvgshapeandtextformattingcontroller/
---

## ISvgShapeAndTextFormattingController interface

Controls SVG shape and text generation.

```csharp
public interface ISvgShapeAndTextFormattingController : ISvgShapeFormattingController
```

## Properties

| Name | Description |
| --- | --- |
| [AsISvgShapeFormattingController](../../aspose.slides.export/isvgshapeandtextformattingcontroller/asisvgshapeformattingcontroller) { get; } | Returns ISvgShapeFormattingController interface. |

## Methods

| Name | Description |
| --- | --- |
| [FormatText](../../aspose.slides.export/isvgshapeandtextformattingcontroller/formattext)(ISvgTSpan, IPortion, ITextFrame) | This function is called before rendering of text portion to SVG to allow user to control resulting SVG. |

### Examples

Example:

```csharp
[C#]
class CustomSvgShapeFormattingController : ISvgShapeAndTextFormattingController
{
	private int m_shapeIndex, m_portionIndex, m_tspanIndex;
	public CustomSvgShapeFormattingController(int shapeStartIndex = 0)
	{
		m_shapeIndex = shapeStartIndex;
		m_portionIndex = 0;
	}
	public void FormatShape(Aspose.Slides.Export.ISvgShape svgShape, IShape shape)
	{
		svgShape.Id = string.Format("shape-{0}", m_shapeIndex++);
		m_portionIndex = m_tspanIndex = 0;
	}
	public void FormatText(Aspose.Slides.Export.ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
	{
		int paragraphIndex = 0; int portionIndex = 0;
		for (int i = 0; i &lt; textFrame.Paragraphs.Count; i++)
		{
			portionIndex = textFrame.Paragraphs[i].Portions.IndexOf(portion);
			if (portionIndex > -1) { paragraphIndex = i; break; }
		}
		if (m_portionIndex != portionIndex)
		{
			m_tspanIndex = 0;
			m_portionIndex = portionIndex;
		}
		svgTSpan.Id = string.Format("paragraph-{0}_portion-{1}_{2}", paragraphIndex, m_portionIndex, m_tspanIndex++);
	}
}
```

### See Also

* interface [ISvgShapeFormattingController](../isvgshapeformattingcontroller)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
