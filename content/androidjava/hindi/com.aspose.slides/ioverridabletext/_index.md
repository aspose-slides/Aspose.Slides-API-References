---
title: IOverridableText
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक चार्ट के लिए ओवरराइड करने योग्य टेक्स्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioverridabletext/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

एक चार्ट के लिए ओवरराइड करने योग्य टेक्स्ट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | रिच फ़ॉर्मेटेड टेक्स्ट रख सकता है। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | पैरामीटर "text" में दिए गए टेक्स्ट के साथ TextFrameForOverriding को प्रारम्भ करें। |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


रिच फ़ॉर्मेटेड टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट मान ऑटो-जनरेटेड टेक्स्ट को ओवरराइड करता है। ऑटो-जनरेटेड टेक्स्ट डेटा लेबल, डिस्प्ले यूनिट लेबल, वैल्यू एक्सिस, एक्सिस टाइटल, चार्ट टाइटल, ट्रेंडलाइन लेबल की एक अभिगामी प्रॉपर्टी है। ऑटो-जनरेटेड टेक्स्ट IFormattedTextContainer.TextFormat प्रॉपर्टी के साथ फ़ॉर्मेट किया गया है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


पैरामीटर "text" में दिए गए टेक्स्ट के साथ TextFrameForOverriding को प्रारम्भ करें। यदि TextFrameForOverriding पहले से प्रारम्भ हो चुका है तो केवल इसका टेक्स्ट बदलता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | नए TextFrameForOverriding के लिए टेक्स्ट। |

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe) - Text frame [ITextFrame](../../com.aspose.slides/itextframe)