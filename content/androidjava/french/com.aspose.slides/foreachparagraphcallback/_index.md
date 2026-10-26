---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /fr/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Rappel qui sera invoqué pour chaque \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sur le [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

Rappel qui sera invoqué pour chaque \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sur le [BaseSlide](../../com.aspose.slides/baseslide).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Paragraphe actuellement itéré |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositive actuellement itérée |
| index | int | Index du paragraphe actuel sur la diapositive |