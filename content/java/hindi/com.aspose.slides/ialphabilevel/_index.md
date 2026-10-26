---
title: IAlphaBiLevel
second_title: Aspose.Slides for Java API संदर्भ
description: एक Alpha Bi-Level प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ialphabilevel/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

एक Alpha Bi-Level इफ़ेक्ट को दर्शाता है। Alpha (Opacity) मान जो थ्रेशोल्ड से कम हैं, उन्हें 0 (पूरी तरह से पारदर्शी) में बदल दिया जाता है और थ्रेशोल्ड के बराबर या अधिक Alpha मानों को 100% (पूरी तरह से अपारदर्शी) में बदल दिया जाता है।

--------------------

COM में इंस्टैंस बनाने के लिए ImageTransformOperationFactory का उपयोग करें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThreshold()](#getThreshold--) | इफ़ेक्ट थ्रेशोल्ड लौटाता है। |
| [setThreshold(float value)](#setThreshold-float-) | इफ़ेक्ट थ्रेशोल्ड लौटाता है। |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

इफ़ेक्ट थ्रेशोल्ड लौटाता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

इफ़ेक्ट थ्रेशोल्ड लौटाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |