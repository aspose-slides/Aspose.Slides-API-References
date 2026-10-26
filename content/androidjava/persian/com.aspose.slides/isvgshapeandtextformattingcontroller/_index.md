---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شکل SVG و تولید متن را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

شکل SVG و تولید متن را کنترل می‌کند.

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
## متدها

| متد | توضیح |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | این تابع قبل از رندر کردن بخش متن به SVG فراخوانی می‌شود تا به کاربر اجازه کنترل SVG تولیدی را بدهد. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


این تابع قبل از رندر کردن بخش متن به SVG فراخوانی می‌شود تا به کاربر اجازه کنترل SVG تولیدی را بدهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | شیءی برای کنترل تولید tspan SVG. |
| portion | [IPortion](../../com.aspose.slides/iportion) | بخش منبع. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | قاب متن بخش منبع. |