---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /hi/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

स्थिर वस्तु जो प्रभावी टेक्स्ट शैली गुणों को शामिल करती है।

--------------------

यह इंटरफ़ेस [ITextStyle](../../com.aspose.slides/itextstyle) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।

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
| index | int | स्तर का शून्य-आधारित सूचकांक। इसे 0..8 अंतराल में होना चाहिए। |

**वापसी:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - स्तर [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) का प्रभावी फ़ॉर्मेटिंग।

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

प्रभावी डिफ़ॉल्ट पैराग्राफ गुण लौटाता है। केवल-पढ़ने योग्य [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)।

**वापसी:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)