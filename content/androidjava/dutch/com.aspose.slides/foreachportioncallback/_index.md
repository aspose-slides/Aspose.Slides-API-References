---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /nl/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback die wordt aangeroepen voor elke \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) op de [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback die wordt aangeroepen voor elke \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) op de [BaseSlide](../../com.aspose.slides/baseslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Huidige doorlopen portion |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Huidige doorlopen paragraph |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Huidige doorlopen slide |
| index | int | Index van de huidige paragraph op de slide |