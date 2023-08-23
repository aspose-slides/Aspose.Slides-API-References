---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback that will be invoked for each \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) on the [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback that will be invoked for each \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) on the [BaseSlide](../../com.aspose.slides/baseslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Current iterated portion |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Current iterated paragraph |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Current iterated slide |
| index | int | Index of the current paragraph on the slide |

