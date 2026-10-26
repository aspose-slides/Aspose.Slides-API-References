---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | कॉलबैक जिसे प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) में [Presentation](../../com.aspose.slides/presentation) के लिए बुलाया जाएगा। |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```


कॉलबैक जिसे प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) में [Presentation](../../com.aspose.slides/presentation) के लिए बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | वर्तमान इटरेटेड लेआउट स्लाइड |
| index | int | वर्तमान लेआउट स्लाइड का सूचकांक |