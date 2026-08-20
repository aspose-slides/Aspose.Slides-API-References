---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /hi/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Text style formatting properties.

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | यदि लेवल ऑफ़ स्टाइल मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है। |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | डिफ़ॉल्ट पैराग्राफ प्रॉपर्टी। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी टेक्स्ट स्टाइल फॉर्मेटिंग डेटा प्राप्त करता है। |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

यदि लेवल ऑफ़ स्टाइल मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लेवल का शून्य-आधारित सूचकांक। इसे 0..8 अंतराल में होना चाहिए। |

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - लेवल [IParagraphFormat](../../com.aspose.slides/iparagraphformat) की फॉर्मेटिंग।

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

डिफ़ॉल्ट पैराग्राफ प्रॉपर्टी। केवल-पढ़ने [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

विरासत लागू करके प्रभावी टेक्स्ट स्टाइल फॉर्मेटिंग डेटा प्राप्त करता है।

**वापसी:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - एक [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)।