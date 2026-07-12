---
title: ISvgShapeAndTextFormattingController
second_title: Referencia de API Java de Aspose.Slides para Android
description: Controla la generación de forma SVG y texto.
type: docs
url: /es/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Controla la forma SVG y la generación de texto.

--------------------

> ```
> Example:
>  
>  class CustomSvgShapeFormattingController implements ISvgShapeAndTextFormattingController
>  {
>      private int m_shapeIndex, m_portionIndex, m_tspanIndex;
> 
>      public CustomSvgShapeFormattingController(int shapeStartIndex)
>      {
>          m_shapeIndex = shapeStartIndex;
>          m_portionIndex = 0;
>      }
>      public void formatShape(ISvgShape svgShape, IShape shape)
>      {
>          svgShape.setId(String.format("shape-%d", m_shapeIndex++));
>          m_portionIndex = m_tspanIndex = 0;
>      }
>      public void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
>      {
>          int paragraphIndex = 0; int portionIndex = 0;
>          for (int i = 0; i < textFrame.getParagraphs().getCount(); i++)
>          {
>              portionIndex = textFrame.getParagraphs().get_Item(i).getPortions().indexOf(portion);
>              if (portionIndex > -1) { paragraphIndex = i; break; }
>          }
>          if (m_portionIndex != portionIndex)
>          {
>              m_tspanIndex = 0;
>              m_portionIndex = portionIndex;
>          }
>          svgTSpan.setId(String.format("paragraph-%d_portion-%d_%d", paragraphIndex, m_portionIndex, m_tspanIndex++));
>      }
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Esta función se llama antes de la renderización de la porción de texto a SVG para permitir al usuario controlar el SVG resultante. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```

Esta función se llama antes de la renderización de la porción de texto a SVG para permitir al usuario controlar el SVG resultante.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Objeto para controlar la generación de tspan SVG. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Porción fuente. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Marco de texto de la porción fuente. |