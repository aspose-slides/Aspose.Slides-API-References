---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides için Java API Referansı
description: SVG şekli ve metin oluşturmayı kontrol eder.
type: docs
url: /tr/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

SVG şekli ve metin oluşturmayı kontrol eder.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Bu işlev, metin bölümünün SVG'ye işlenmeden önce çağrılır ve kullanıcının oluşan SVG'yi kontrol etmesine olanak tanır. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Bu işlev, metin bölümünün SVG'ye işlenmeden önce çağrılır ve kullanıcının oluşan SVG'yi kontrol etmesine olanak tanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | SVG tspan oluşturmayı kontrol etmek için nesne. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Kaynak bölüm. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Kaynak bölüm metin çerçevesi. |