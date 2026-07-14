---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: SVG आकार और टेक्स्ट निर्माण को नियंत्रित करता है।
type: docs
url: /hi/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

SVG आकार और टेक्स्ट जेनरेशन को नियंत्रित करता है।

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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | यह फ़ंक्शन टेक्स्ट भाग को SVG में रेंडर करने से पहले बुलाया जाता है ताकि उपयोगकर्ता परिणामस्वरूप SVG को नियंत्रित कर सके। |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```

यह फ़ंक्शन टेक्स्ट भाग को SVG में रेंडर करने से पहले बुलाया जाता है ताकि उपयोगकर्ता परिणामस्वरूप SVG को नियंत्रित कर सके।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | SVG tspan निर्माण को नियंत्रित करने के लिए ऑब्जेक्ट। |
| portion | [IPortion](../../com.aspose.slides/iportion) | स्रोत भाग। |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | स्रोत भाग का टेक्स्ट फ़्रेम। |