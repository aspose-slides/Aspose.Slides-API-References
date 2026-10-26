---
title: PortionFormat
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: यह वर्ग पाठ भाग फ़ॉर्मेटिंग गुणों को सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/portionformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

यह वर्ग पाठ भाग फ़ॉर्मेटिंग गुणों को सम्मिलित करता है। [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) के विपरीत, इस वर्ग की सभी गुण लिखने योग्य हैं।

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करने वाला एक प्रेजेंटेशन ऑब्जेक्ट बनाता है
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides इन विशेष पहचानकर्ताओं का उपयोग करता है (PowerPoint में उपयोग किए जाने वाले समान):
>      // +mn-lt - बॉडी फ़ॉन्ट लैटिन (माइनर लैटिन फ़ॉन्ट)
>      // +mj-lt - हेडिंग फ़ॉन्ट लैटिन (मैजर लैटिन फ़ॉन्ट)
>      // +mn-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
>      // +mj-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

यह वर्ग विशेष भाग के लिए परिभाषित पाठ भाग फ़ॉर्मेटिंग गुणों को लौटाने और संशोधित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मान मिलेंगे जो "अपरिभाषित" को दर्शाते हैं।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/portionformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | एक नया [PortionFormat](../../com.aspose.slides/portionformat) क्लास का उदाहरण आरंभीकृत करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | बुकमार्क पहचानकर्ता को लौटाता या सेट करता है। |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | बुकमार्क पहचानकर्ता को लौटाता या सेट करता है। |
| [getSmartTagClean()](#getSmartTagClean--) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [getHyperlinkClick()](#getHyperlinkClick--) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [getHyperlinkManager()](#getHyperlinkManager--) | हाइपरलिंक्स प्रबंधक। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


एक नया [PortionFormat](../../com.aspose.slides/portionformat) क्लास का उदाहरण आरंभीकृत करता है।

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


बुकमार्क पहचानकर्ता को लौटाता या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


बुकमार्क पहचानकर्ता को लौटाता या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें boolean .

**रिटर्न:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें boolean .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


हाइपरलिंक प्रबंधक। केवल-पढ़ने योग्य [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**रिटर्न:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).