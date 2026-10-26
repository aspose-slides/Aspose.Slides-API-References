---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API संदर्भ
description: टेक्स्ट शैली फ़ॉर्मेटिंग गुण।
type: docs
url: /hi/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

टेक्स्ट शैली फ़ॉर्मेटिंग गुण।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | यदि शैली का स्तर मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है। |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | डिफ़ॉल्ट पैराग्राफ प्रॉपर्टीज़। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी टेक्स्ट शैली फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

यदि शैली का स्तर मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | स्तर का शून्य-आधारित सूचकांक। यह 0..8 अंतराल में होना चाहिए। |

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - स्तर [IParagraphFormat](../../com.aspose.slides/iparagraphformat) का फ़ॉर्मेटिंग।

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

डिफ़ॉल्ट पैराग्राफ प्रॉपर्टीज़। केवल पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी टेक्स्ट शैली फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**वापसी:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - एक [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)।