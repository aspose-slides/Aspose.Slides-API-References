---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides para Android via Referência da API Java
description: Controla a forma SVG e a geração de texto.
type: docs
url: /pt/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Controla a forma e a geração de texto SVG.

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

| Método | Descrição |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Esta função é chamada antes da renderização da parte de texto para SVG para permitir que o usuário controle o SVG resultante. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```

Esta função é chamada antes da renderização da parte de texto para SVG para permitir que o usuário controle o SVG resultante.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Objeto para controlar a geração de tspan SVG. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Porção de origem. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto da porção de origem. |
