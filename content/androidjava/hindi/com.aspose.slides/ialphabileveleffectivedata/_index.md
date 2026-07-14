---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो Alpha Bi-Level प्रभाव का प्रतिनिधित्व करती है।
type: docs
url: /hi/com.aspose.slides/ialphabileveleffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय वस्तु जो एक Alpha Bi-Level प्रभाव का प्रतिनिधित्व करती है। Alpha (Opacity) मान जो थ्रेशहोल्ड से कम हैं, उन्हें 0 (पूरी तरह पारदर्शी) में बदल दिया जाता है और alpha मान जो थ्रेशहोल्ड से बड़ा या बराबर हैं, उन्हें 100 % (पूरी तरह अपारदर्शी) में बदल दिया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThreshold()](#getThreshold--) | इफ़ेक्ट थ्रेशहोल्ड लौटाता है। |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


इफ़ेक्ट थ्रेशहोल्ड लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float