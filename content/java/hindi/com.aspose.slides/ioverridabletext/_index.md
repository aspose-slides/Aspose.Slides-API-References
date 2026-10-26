---
title: IOverridableText
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक चार्ट के लिए ओवरराइडेबल टेक्स्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioverridabletext/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

एक चार्ट के लिए ओवरराइडेबल टेक्स्ट का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | रिच फ़ॉर्मेटेड टेक्स्ट शामिल कर सकता है। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialize TextFrameForOverriding with the text in paramener "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

रिच फ़ॉर्मेटेड टेक्स्ट शामिल कर सकता है। यदि यह प्रॉपर्टी नल नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट मान ऑटो-जेनरेटेड टेक्स्ट को ओवरराइड करता है। ऑटो-जेनरेटेड टेक्स्ट डेटा लेबल, वैल्यू एक्सिस के डिस्प्ले यूनिट लेबल, एक्सिस टाइटल, चार्ट टाइटल, ट्रेंडलाइन लेबल की एक अंतर्निहित प्रॉपर्टी है। ऑटो-जेनरेटेड टेक्स्ट IFormattedTextContainer.TextFormat प्रॉपर्टी द्वारा फ़ॉर्मेट किया गया है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Initialize TextFrameForOverriding with the text in paramener "text". यदि TextFrameForOverriding पहले से इनिशियलाइज़्ड है तो केवल उसका टेक्स्ट बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई TextFrameForOverriding के लिए टेक्स्ट। |

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe) - Text frame [ITextFrame](../../com.aspose.slides/itextframe)