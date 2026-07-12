---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides für Android über Java API-Referenz
description: Steuert die SVG-Form und die Textgenerierung.
type: docs
url: /de/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Steuert die SVG-Form und die Textgenerierung.

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

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Diese Funktion wird vor dem Rendern des Textabschnitts zu SVG aufgerufen, um dem Benutzer zu ermöglichen, das resultierende SVG zu steuern. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Diese Funktion wird vor dem Rendern des Textabschnitts zu SVG aufgerufen, um dem Benutzer zu ermöglichen, das resultierende SVG zu steuern.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Objekt zur Steuerung der SVG-tspan-Generierung. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Quellabschnitt. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quellabschnitt-Textfeld. |