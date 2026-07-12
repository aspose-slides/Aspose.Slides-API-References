---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | Visszahívás, amely minden \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ben. |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

Visszahívás, amely minden \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | Aktuális iterált elrendezési dia |
| index | int | Az aktuális elrendezési dia indexe |