---
title: IBackgroundEffectiveData
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ
description: एक अपरिवर्तनीय वस्तु जिसमें प्रभावी पृष्ठभूमि गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/ibackgroundeffectivedata/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

एक अपरिवर्तनीय वस्तु जिसमें प्रभावी पृष्ठभूमि गुण होते हैं।

--------------------

यह इंटरफ़ेस [IBackground](../../com.aspose.slides/ibackground) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | प्रभावी fill format लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | प्रभावी effect format लौटाता है। |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

प्रभावी fill format लौटाता है। केवल-पढ़ने-योग्य [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)।

**रिटर्न:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

प्रभावी effect format लौटाता है। केवल-पढ़ने-योग्य [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)।

**रिटर्न:**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)