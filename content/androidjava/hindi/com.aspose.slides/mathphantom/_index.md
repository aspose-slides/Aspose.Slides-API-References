---
title: MathPhantom
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक phantom गणितीय वस्तु ltmphantgt का प्रतिनिधित्व करता है जो अपने बाल तत्व के लेआउट को प्रभावित करता है बिना आवश्यक रूप से उसे प्रदर्शित किए।
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

एक phantom गणित वस्तु (<m:phant>) का प्रतिनिधित्व करता है जो अपने बाल तत्व की लेआउट को प्रभावित करता है बिना आवश्यक रूप से उसे प्रदर्शित किए। एक phantom अपना बेस अभिव्यक्ति छिपा सकता है जबकि उसकी चौड़ाई, ऊँचाई या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। विजिबिलिटी और ज्यामिति व्यवहार Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // सामग्री छुपाएँ
>  phantom.setZeroWidth(false);     // चौड़ाई बनाए रखें
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | निर्दिष्ट बेस गणित तत्व का उपयोग करके [MathPhantom](../../com.aspose.slides/mathphantom) क्लास की नई उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getShow()](#getShow--) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setShow(boolean value)](#setShow-boolean-) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getZeroWidth()](#getZeroWidth--) | बेस तत्व की चौड़ाई को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | बेस तत्व की चौड़ाई को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getZeroAsc()](#getZeroAsc--) | बेस तत्व की आरोह (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | बेस तत्व की आरोह (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getZeroDesc()](#getZeroDesc--) | बेस तत्व की अवरोह (बेसलाइन के नीचे की गहराई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | बेस तत्व की अवरोह (बेसलाइन के नीचे की गहराई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getTransp()](#getTransp--) | वर्ग-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setTransp(boolean value)](#setTransp-boolean-) | वर्ग-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण अक्षर गुण |
| [getChildren()](#getChildren--) | बाल तत्व प्राप्त करें |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

निर्दिष्ट बेस गणित तत्व का उपयोग करके [MathPhantom](../../com.aspose.slides/mathphantom) क्लास की नई उदाहरण प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस [IMathElement](../../com.aspose.slides/imathelement) जिसकी विजिबिलिटी और लेआउट phantom द्वारा नियंत्रित किया जाएगा। यह तत्व वह सामग्री परिभाषित करता है जिसे छिपाया या दिखाया जा सकता है, जबकि फिर भी आस-पास के गणित की ज्यामितीय संरेखण को प्रभावित करता है। |
फ़ैंटम एलिमेंट का उपयोग उसके बेस अभिव्यक्ति के दृश्य स्थान को आरक्षित या दमन करने के लिए किया जाता है बिना आवश्यक रूप से उसे प्रदर्शित किए। यह OMML तत्व <m:phant> के समान है। |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

जब false होता है, बेस तत्व छिपा रहता है लेकिन अन्य phantom सेटिंग्स के आधार पर अभी भी स्थान ले सकता है। यह OMML विशेषता m:show के अनुरूप है।

**वापसी:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

बेस तत्व की चौड़ाई को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

जब true होता है, phantom बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML विशेषता m:zeroWid के अनुरूप है।

**वापसी:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

बेस तत्व की चौड़ाई को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

बेस तत्व की आरोह (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

जब true होता है, phantom आस-पास की गणित लाइन की बेसलाइन को नहीं उठाता। यह OMML विशेषता m:zeroAsc के अनुरूप है।

**वापसी:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

बेस तत्व की आरोह (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

बेस तत्व की अवरोह (बेसलाइन के नीचे की गहराई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

जब true होता है, phantom आस-पास की गणित लाइन की बेसलाइन को नहीं नीचे लाता। यह OMML विशेषता m:zeroDesc के अनुरूप है।

**वापसी:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

बेस तत्व की अवरोह (बेसलाइन के नीचे की गहराई) को शून्य माना जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

phantom वर्ग-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

जब true होता है, phantom के अंदर के ऑपरेटर और प्रतीक अभी भी phantom के आसपास की गणितीय स्पेसिंग को प्रभावित करते हैं (जैसे कि वे दृश्यमान हों)। जब false होता है, वर्ग-आधारित स्पेसिंग को अनदेखा किया जाता है। यह OMML विशेषता m:transp के अनुरूप है।

**वापसी:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

phantom वर्ग-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण अक्षर गुण

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बाल तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]