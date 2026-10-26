---
title: ISvgShapeAndTextFormattingController
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: SVG 모양 및 텍스트 생성을 제어합니다.
type: docs
url: /ko/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

SVG 모양 및 텍스트 생성을 제어합니다.

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
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | 이 함수는 텍스트 부분을 SVG로 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있도록 합니다. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


이 함수는 텍스트 부분을 SVG로 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있도록 합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | SVG tspan 생성을 제어하는 객체. |
| portion | [IPortion](../../com.aspose.slides/iportion) | 소스 부분. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 소스 부분 텍스트 프레임. |