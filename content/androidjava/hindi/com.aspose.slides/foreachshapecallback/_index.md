---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hi/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | प्रत्येक [Shape](../../com.aspose.slides/shape) के लिए कॉलबैक जो [Presentation](../../com.aspose.slides/presentation) में बुलाया जाएगा। |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

प्रत्येक [Shape](../../com.aspose.slides/shape) के लिए कॉलबैक जो [Presentation](../../com.aspose.slides/presentation) में बुलाया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | वर्तमान दोहराया गया आकार |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | वर्तमान दोहराया गया स्लाइड |
| index | int | वर्तमान लेआउट स्लाइड का इंडेक्स |