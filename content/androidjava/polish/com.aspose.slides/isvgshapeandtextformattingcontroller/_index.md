---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Kontroluje generowanie kształtu SVG i tekstu.
type: docs
url: /pl/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Kontroluje kształt SVG i generowanie tekstu.

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
## Metody

| Metoda | Opis |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Ta funkcja jest wywoływana przed renderowaniem części tekstowej do SVG, aby umożliwić użytkownikowi kontrolę nad wynikowym SVG. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Ta funkcja jest wywoływana przed renderowaniem części tekstowej do SVG, aby umożliwić użytkownikowi kontrolę nad wynikowym SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Obiekt służący do kontrolowania generowania elementu tspan SVG. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Źródłowa część. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Ramka tekstowa źródłowej części. |