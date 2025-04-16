---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback that will be invoked for each [.paragraph(Presentation,ForEachParagraphCallback)](../../null/\#paragraph-Presentation-ForEachParagraphCallback-) on the [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


Callback that will be invoked for each [.paragraph(Presentation,ForEachParagraphCallback)](../../null/\#paragraph-Presentation-ForEachParagraphCallback-) on the [BaseSlide](../../com.aspose.slides/baseslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Current iterated paragraph |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Current iterated slide |
| index | int | Index of the current paragraph on the slide |

