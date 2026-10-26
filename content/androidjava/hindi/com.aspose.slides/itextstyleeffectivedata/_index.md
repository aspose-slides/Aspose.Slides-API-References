---
title: ITextStyleEffectiveData
second_title: Aspose.Slides एंड्रॉइड के लिए Java API संदर्भ
description: अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी टेक्स्ट शैली गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी टेक्स्ट शैली गुण होते हैं।

--------------------

यह इंटरफ़ेस [ITextStyle](../../com.aspose.slides/itextstyle) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | प्रभावी शैली का स्तर लौटाता है। |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | प्रभावी डिफ़ॉल्ट पैराग्राफ गुण लौटाता है। |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

प्रभावी शैली का स्तर लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | स्तर का शून्य-आधारित सूचकांक। 0..8 अंतराल में होना चाहिए। |

**रिटर्न मान:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - स्तर [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) का प्रभावी स्वरूपण।

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

प्रभावी डिफ़ॉल्ट पैराग्राफ गुण लौटाता है। केवल-पढ़ने योग्य [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)।

**रिटर्न मान:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)