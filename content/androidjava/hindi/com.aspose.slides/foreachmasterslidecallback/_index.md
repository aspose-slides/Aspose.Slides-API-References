---
title: ForEach.ForEachMasterSlideCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachmasterslidecallback/
---```
public static interface ForEach.ForEachMasterSlideCallback
```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [invoke(MasterSlide masterSlide, int index)](#invoke-com.aspose.slides.MasterSlide-int-) | कॉलबैक जिसे प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) के लिए [Presentation](../../com.aspose.slides/presentation) में बुलाया जाएगा। |
### invoke(MasterSlide masterSlide, int index) {#invoke-com.aspose.slides.MasterSlide-int-}
```
public abstract void invoke(MasterSlide masterSlide, int index)
```

कॉलबैक जिसे प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) के लिए [Presentation](../../com.aspose.slides/presentation) में बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| masterSlide | [MasterSlide](../../com.aspose.slides/masterslide) | वर्तमान क्रमबद्ध मास्टर स्लाइड |
| index | int | वर्तमान मास्टर स्लाइड का इंडेक्स |