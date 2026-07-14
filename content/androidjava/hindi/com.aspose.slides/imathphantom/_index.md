---
title: IMathPhantom
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: ltmphantgt नामक एक phantom गणितीय वस्तु को दर्शाता है जो अपने संतान तत्व की लेआउट को प्रभावित करता है बिना ज़रूरी तौर पर उसे प्रदर्शित किए।
type: docs
url: /hi/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

एक phantom गणितीय वस्तु (<m:phant>) को दर्शाता है जो अपने संतान तत्व की लेआउट को प्रभावित करती है बिना ज़रूरी तौर पर उसे प्रदर्शित किए। एक phantom अपनी बेस अभिव्यक्ति को छुपा सकता है जबकि उसकी चौड़ाई, ऊँचाई, या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यमानता और ज्यामितीय व्यवहार Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित होते हैं।

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // सामग्री को छिपाएँ
>  phantom.setZeroWidth(false);     // चौड़ाई रखें
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getShow()](#getShow--) | बेस तत्व प्रदर्शित है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [setShow(boolean value)](#setShow-boolean-) | बेस तत्व प्रदर्शित है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [getZeroWidth()](#getZeroWidth--) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [getZeroAsc()](#getZeroAsc--) | बेस तत्व की आरोहण (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | बेस तत्व की आरोहण (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [getZeroDesc()](#getZeroDesc--) | बेस तत्व की अवरोहण (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | बेस तत्व की अवरोहण (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [getTransp()](#getTransp--) | क्लास-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
| [setTransp(boolean value)](#setTransp-boolean-) | क्लास-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


बेस तर्क

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
public abstract boolean getShow()
```


बेस तत्व प्रदर्शित है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब false हो, बेस तत्व छिपा रहता है लेकिन अन्य phantom सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML विशेषता m:show के अनुरूप है।

**रिटर्न:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


बेस तत्व प्रदर्शित है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब false हो, बेस तत्व छिपा रहता है लेकिन अन्य phantom सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML विशेषता m:show के अनुरूप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML विशेषता m:zeroWid के अनुरूप है।

**रिटर्न:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML विशेषता m:zeroWid के अनुरूप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


बेस तत्व की आरोहण (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom आस-पास की गणितीय पंक्ति की बेसलाइन को नहीं उठाता। यह OMML विशेषता m:zeroAsc के अनुरूप है।

**रिटर्न:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


बेस तत्व की आरोहण (बेसलाइन से ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom आस-पास की गणितीय पंक्ति की बेसलाइन को नहीं उठाता। यह OMML विशेषता m:zeroAsc के अनुरूप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


बेस तत्व की अवरोहण (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom आस-पास की गणितीय पंक्ति की बेसलाइन को नहीं घटाता। यह OMML विशेषता m:zeroDesc के अनुरूप है।

**रिटर्न:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


बेस तत्व की अवरोहण (बेसलाइन से नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom आस-पास की गणितीय पंक्ति की बेसलाइन को नहीं घटाता। यह OMML विशेषता m:zeroDesc के अनुरूप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


क्लास-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom के भीतर के ऑपरेटर और प्रतीक अभी भी phantom के चारों ओर गणितीय स्पेसिंग को प्रभावित करते हैं (जैसे यह दृश्यमान हो)। जब false हो, क्लास-आधारित स्पेसिंग को अनदेखा किया जाता है। यह OMML विशेषता m:transp के अनुरूप है।

**रिटर्न:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


क्लास-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं यह दर्शाने वाला मान प्राप्त या स्थापित करता है।

--------------------

जब true हो, phantom के भीतर के ऑपरेटर और प्रतीक अभी भी phantom के चारों ओर गणितीय स्पेसिंग को प्रभावित करते हैं (जैसे यह दृश्यमान हो)। जब false हो, क्लास-आधारित स्पेसिंग को अनदेखा किया जाता है। यह OMML विशेषता m:transp के अनुरूप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |