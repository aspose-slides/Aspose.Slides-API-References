---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides Androidhoz Java API Referencián keresztül
description: Az SVG alakzat és szöveg generálását vezérli.
type: docs
url: /hu/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Az SVG alakzat és szöveg generálásának vezérlése.

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
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Ez a függvény a szövegrész SVG-re történő renderelése előtt hívódik meg, hogy a felhasználó irányíthassa a keletkező SVG-t. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Ez a függvény a szövegrész SVG-re történő renderelése előtt hívódik meg, hogy a felhasználó irányíthassa a keletkező SVG-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Az SVG tspan generálásának vezérlésére szolgáló objektum. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Forrásrész. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Forrásrész szövegkerete. |