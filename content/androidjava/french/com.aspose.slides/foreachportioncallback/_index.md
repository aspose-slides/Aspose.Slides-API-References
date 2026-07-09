---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /fr/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Rappel qui sera invoqué pour chaque \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sur le [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Rappel qui sera invoqué pour chaque \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sur le [BaseSlide](../../com.aspose.slides/baseslide).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Portion actuelle parcourue |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Paragraphe actuel parcouru |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositive actuelle parcourue |
| index | int | Indice du paragraphe actuel sur la diapositive |
