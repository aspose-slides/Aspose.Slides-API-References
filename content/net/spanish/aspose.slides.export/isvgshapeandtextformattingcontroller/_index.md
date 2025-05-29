---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides para .NET Referencia de API
description: Controla la generación de forma SVG y texto.
type: docs
weight: 3950
url: /es/aspose.slides.export/isvgshapeandtextformattingcontroller/
---

## Interfaz ISvgShapeAndTextFormattingController

Controla la generación de forma SVG y texto.

```csharp
public interface ISvgShapeAndTextFormattingController : ISvgShapeFormattingController
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISvgShapeFormattingController](../../aspose.slides.export/isvgshapeandtextformattingcontroller/asisvgshapeformattingcontroller) { get; } | Devuelve la interfaz ISvgShapeFormattingController. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FormatText](../../aspose.slides.export/isvgshapeandtextformattingcontroller/formattext)(ISvgTSpan, IPortion, ITextFrame) | Esta función se llama antes de renderizar la porción de texto a SVG para permitir al usuario controlar el SVG resultante. |

### Ejemplos

Ejemplo:

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

### Véase También

* interfaz [ISvgShapeFormattingController](../isvgshapeformattingcontroller)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->