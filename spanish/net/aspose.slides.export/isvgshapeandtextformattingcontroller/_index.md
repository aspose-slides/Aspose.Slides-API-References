---
title: ISvgShapeAndTextFormattingController
second_title: Referencia de la API de Aspose.Slides para .NET
description: Controla la forma SVG y la generación de texto.
type: docs
weight: 3780
url: /es/net/aspose.slides.export/isvgshapeandtextformattingcontroller/
---
## ISvgShapeAndTextFormattingController interface

Controla la forma SVG y la generación de texto.

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
| [FormatText](../../aspose.slides.export/isvgshapeandtextformattingcontroller/formattext)(ISvgTSpan, IPortion, ITextFrame) | Se llama a esta función antes de representar la porción de texto en SVG para permitir que el usuario controle el SVG resultante. |

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
		for (int i = 0; i < textFrame.Paragraphs.Count; i++)
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

### Ver también

* interface [ISvgShapeFormattingController](../isvgshapeformattingcontroller)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->