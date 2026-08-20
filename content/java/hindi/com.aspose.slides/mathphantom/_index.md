---
title: MathPhantom
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक फ़ैंटम गणितीय ऑब्जेक्ट ltmphantgt का प्रतिनिधित्व करता है जो इसके चाइल्ड एलिमेंट के लेआउट को प्रभावित करता है, लेकिन आवश्यक रूप से उसे प्रदर्शित नहीं करता।
type: docs
url: /hi/com.aspose.slides/mathphantom/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

एक फ़ैंटम गणितीय ऑब्जेक्ट (<m:phant>) का प्रतिनिधित्व करता है जो इसके चाइल्ड एलिमेंट की लेआउट को प्रभावित करता है लेकिन अनिवार्य रूप से उसे प्रदर्शित नहीं करता। एक फ़ैंटम अपने बेस एक्सप्रेशन को छिपा सकता है जबकि इसकी चौड़ाई, ऊँचाई या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यमानता और ज्यामितीय व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // सामग्री को छुपाएँ
>  phantom.setZeroWidth(false);     // चौड़ाई रखें
> ```
## निर्माताएँ

| निर्मात्‍ता | विवरण |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | निर्दिष्ट बेस गणितीय तत्व का उपयोग करके [MathPhantom](../../com.aspose.slides/mathphantom) क्लास का नया उदाहरण आरम्भ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getShow()](#getShow--) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setShow(boolean value)](#setShow-boolean-) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getZeroWidth()](#getZeroWidth--) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getZeroAsc()](#getZeroAsc--) | बेस तत्व की उन्नति (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | बेस तत्व की उन्नति (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getZeroDesc()](#getZeroDesc--) | बेस तत्व की अवनति (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | बेस तत्व की अवनति (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getTransp()](#getTransp--) | क्लास-आधारित स्पेसिंग नियमों के लिए फ़ैंटम पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [setTransp(boolean value)](#setTransp-boolean-) | क्लास-आधारित स्पेसिंग नियमों के लिए फ़ैंटम पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण अक्षर गुण |
| [getChildren()](#getChildren--) | चाइल्ड तत्व प्राप्त करें |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

निर्दिष्ट बेस गणितीय तत्व का उपयोग करके [MathPhantom](../../com.aspose.slides/mathphantom) क्लास का नया उदाहरण आरम्भ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बेस [IMathElement](../../com.aspose.slides/imathelement) जिसकी दृश्यमानता और लेआउट फ़ैंटम द्वारा नियंत्रित होगा। यह तत्व वह सामग्री परिभाषित करता है जिसे छिपाया या दिखाया जा सकता है, फिर भी यह आसपास की गणितीय संरेखण को प्रभावित करता है। |

--------------------

फ़ैंटम तत्व उसके बेस एक्सप्रेशन के दृश्य स्थान को आरक्षित या दमन करने के लिए उपयोग किया जाता है बिना अनिवार्य रूप से इसे प्रदर्शित किए। यह OMML तत्व <m:phant> के अनुरूप है। |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब false होता है, बेस तत्व छिपा रहता है लेकिन अन्य फ़ैंटम सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML attribute m:show के अनुरूप है।

**रिटर्न:**  
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब false होता है, बेस तत्व छिपा रहता है लेकिन अन्य फ़ैंटम सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML attribute m:show के अनुरूप है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML attribute m:zeroWid के अनुरूप है।

**रिटर्न:**  
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML attribute m:zeroWid के अनुरूप है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

बेस तत्व की उन्नति (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नहीं उठाता। यह OMML attribute m:zeroAsc के अनुरूप है।

**रिटर्न:**  
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

बेस तत्व की उन्नति (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नहीं उठाता। यह OMML attribute m:zeroAsc के अनुरूप है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

बेस तत्व की अवनति (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नीचे नहीं करता। यह OMML attribute m:zeroDesc के अनुरूप है।

**रिटर्न:**  
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

बेस तत्व की अवनति (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नीचे नहीं करता। यह OMML attribute m:zeroDesc के अनुरूप है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

फ़ैंटम क्लास-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम के भीतर के ऑपरेटर और प्रतीक अभी भी फ़ैंटम के आसपास की गणितीय स्पेसिंग को प्रभावित करते हैं (मानो दृश्यमान हों)। जब false होता है, क्लास-आधारित स्पेसिंग अनदेखा किया जाता है। यह OMML attribute m:transp के अनुरूप है।

**रिटर्न:**  
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

फ़ैंटम क्लास-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।

--------------------

जब true होता है, फ़ैंटम के भीतर के ऑपरेटर और प्रतीक अभी भी फ़ैंटम के आसपास की गणितीय स्पेसिंग को प्रभावित करते हैं (मानो दृश्यमान हों)। जब false होता है, क्लास-आधारित स्पेसिंग अनदेखा किया जाता है। यह OMML attribute m:transp के अनुरूप है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण अक्षर गुण

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

चाइल्ड तत्व प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[]