---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Kiểm soát việc tạo hình dạng SVG và văn bản.
type: docs
url: /vi/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Kiểm soát hình dạng SVG và tạo đoạn văn bản.

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

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Hàm này được gọi trước khi phần văn bản được vẽ ra SVG để cho phép người dùng kiểm soát SVG kết quả. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Hàm này được gọi trước khi phần văn bản được vẽ ra SVG để cho phép người dùng kiểm soát SVG kết quả.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Đối tượng để kiểm soát việc tạo SVG tspan. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Phần nguồn. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Khung văn bản của phần nguồn. |