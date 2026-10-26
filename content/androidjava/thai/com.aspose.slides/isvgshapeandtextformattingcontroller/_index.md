---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ควบคุมการสร้างรูปทรง SVG และข้อความ.
type: docs
url: /th/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**อินเทอร์เฟซทั้งหมดที่ทำการนำไปใช้:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

ควบคุมการสร้างรูปแบบ SVG และข้อความ.

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

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | ฟังก์ชันนี้จะถูกเรียกก่อนการเรนเดอร์ส่วนของข้อความเป็น SVG เพื่อให้ผู้ใช้สามารถควบคุม SVG ที่ได้. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


ฟังก์ชันนี้จะถูกเรียกก่อนการเรนเดอร์ส่วนของข้อความเป็น SVG เพื่อให้ผู้ใช้สามารถควบคุม SVG ที่ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | อ็อบเจกต์เพื่อควบคุมการสร้าง tspan ของ SVG. |
| portion | [IPortion](../../com.aspose.slides/iportion) | ส่วนต้นทาง. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | เฟรมข้อความของส่วนต้นทาง. |