---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: अपरिवर्तनीय वस्तु जिसमें प्रभावी पाठ भाग स्वरूपण गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/iportionformateffectivedata/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

अपरिवर्तनीय वस्तु जिसमें प्रभावी पाठ भाग स्वरूपण गुण होते हैं।

--------------------

यह इंटरफ़ेस [IPortionFormat](../../com.aspose.slides/iportionformat) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासती लागू किए गए प्रभावी स्वरूपण मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | बुकमार्क पहचानकर्ता लौटाता है। |
| [getHyperlinkClick()](#getHyperlinkClick--) | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

बुकमार्क पहचानकर्ता लौटाता है। केवल-पढ़ने-योग्य String।

**वापसी:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। केवल-पढ़ने-योग्य [IHyperlink](../../com.aspose.slides/ihyperlink)।

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। केवल-पढ़ने-योग्य [IHyperlink](../../com.aspose.slides/ihyperlink)।

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink)