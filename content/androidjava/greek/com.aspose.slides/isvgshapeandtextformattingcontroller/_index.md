---
title: ISvgShapeAndTextFormattingController
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Ελέγχει τη δημιουργία σχήματος SVG και κειμένου.
type: docs
url: /el/com.aspose.slides/isvgshapeandtextformattingcontroller/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
```
public interface ISvgShapeAndTextFormattingController extends ISvgShapeFormattingController
```

Ελέγχει το σχήμα SVG και τη δημιουργία κειμένου.

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

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)](#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-) | Αυτή η λειτουργία καλείται πριν από τη δημιουργία του τμήματος κειμένου σε SVG για να επιτρέψει στον χρήστη να ελέγξει το προκύπτον SVG. |
### formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame) {#formatText-com.aspose.slides.ISvgTSpan-com.aspose.slides.IPortion-com.aspose.slides.ITextFrame-}
```
public abstract void formatText(ISvgTSpan svgTSpan, IPortion portion, ITextFrame textFrame)
```


Αυτή η λειτουργία καλείται πριν από τη δημιουργία του τμήματος κειμένου σε SVG για να επιτρέψει στον χρήστη να ελέγξει το προκύπτον SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgTSpan | [ISvgTSpan](../../com.aspose.slides/isvgtspan) | Αντικείμενο για τον έλεγχο της δημιουργίας SVG tspan. |
| portion | [IPortion](../../com.aspose.slides/iportion) | Πηγαίο τμήμα. |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Πλαισίο κειμένου του πηγαίου τμήματος. |