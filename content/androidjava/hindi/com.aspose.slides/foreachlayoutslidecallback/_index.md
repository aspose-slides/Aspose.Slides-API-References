---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | Callback that will be invoked for each \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) in the [Presentation](../../com.aspose.slides/presentation). |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

प्रत्येक #layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) के लिए कॉलबैक को [Presentation](../../com.aspose.slides/presentation) में बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | वर्तमान प्रवर्तित लेआउट स्लाइड |
| index | int | वर्तमान लेआउट स्लाइड का सूचकांक |