---
title: ISvgShapeAndTextFormattingController
second_title: Справочник API Aspose.Slides для Java
description: Управляет генерацией SVG-форм и текста.
type: docs
url: /ru/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Управляет генерацией SVG-форм и текста.

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
## Методы

| Метод | Описание |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Эта функция вызывается перед рендерингом текстовой части в SVG, чтобы позволить пользователю контролировать получающийся SVG. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```

Эта функция вызывается перед рендерингом текстовой части в SVG, чтобы позволить пользователю контролировать получающийся SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Объект для управления генерацией SVG-tspan. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Исходная часть. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый фрейм исходной части. |