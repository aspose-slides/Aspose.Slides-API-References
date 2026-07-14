---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो द्वि-स्तरीय काला/सफेद प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibileveleffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

एक अपरिवर्तनीय ऑब्जेक्ट जो द्वि-स्तरीय (काला/सफेद) प्रभाव का प्रतिनिधित्व करता है। इनपुट रंग जिनकी चमक निर्दिष्ट थ्रैशहोल्ड मान से कम है, उन्हें काले में बदल दिया जाता है। इनपुट रंग जिनकी चमक निर्दिष्ट मान के बराबर या अधिक है, उन्हें सफेद पर सेट किया जाता है। अल्फा प्रभाव मान इस प्रभाव द्वारा अप्रभावित रहते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThreshold()](#getThreshold--) | थ्रैशहोल्ड मान को लौटाता है। |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

थ्रैशहोल्ड मान को लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float