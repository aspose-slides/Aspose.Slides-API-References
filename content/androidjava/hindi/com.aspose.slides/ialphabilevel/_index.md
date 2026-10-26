---
title: IAlphaBiLevel
second_title: Aspose.Slides Android के लिए Java API Reference के माध्यम से
description: एक अल्फा द्वि-स्तरीय प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ialphabilevel/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

एक अल्फा द्वि-स्तरीय प्रभाव का प्रतिनिधित्व करता है। थ्रेशहोल्ड से कम अल्फा (Opacity) मान 0 (पूरी तरह से पारदर्शी) में बदल दिए जाते हैं और थ्रेशहोल्ड के बराबर या अधिक अल्फा मान 100% (पूरी तरह से अपारदर्शी) में बदल दिए जाते हैं।

--------------------

COM में इंस्टेंस बनाने के लिए ImageTransformOperationFactory का उपयोग करें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThreshold()](#getThreshold--) | प्रभाव थ्रेशहोल्ड लौटाता है। |
| [setThreshold(float value)](#setThreshold-float-) | प्रभाव थ्रेशहोल्ड लौटाता है। |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

प्रभाव थ्रेशहोल्ड लौटाता है। पढ़ें/लिखें float.

**रिटर्न:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

प्रभाव थ्रेशहोल्ड लौटाता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |