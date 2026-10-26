---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /fr/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback that will be invoked for each \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) on the [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback that will be invoked for each \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) on the [BaseSlide](../../com.aspose.slides/baseslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Portion itérée actuelle |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Paragraphe itéré actuel |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositive itérée actuelle |
| index | int | Indice du paragraphe actuel sur la diapositive |