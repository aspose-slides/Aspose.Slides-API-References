---
title: IMathPhantom
second_title: Aspose.Slides के लिए Java API संदर्भ
description: ltmphantgt नामक एक फ़ैंटम गणित वस्तु को दर्शाता है जो अपने उप-तत्व की लेआउट को प्रभावित करता है, भले ही वह हमेशा प्रदर्शित न हो।
type: docs
url: /hi/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Represents a phantom math object (<m:phant>) that affects the layout of its child element without necessarily displaying it. A phantom can hide its base expression while preserving its width, height, or depth to align formulas or reserve space. Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, ZeroDesc, and Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // सामग्री छिपाएँ
>  phantom.setZeroWidth(false);     // चौड़ाई रखें
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [setShow(boolean value)](#setShow-boolean-) | बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [getZeroWidth()](#getZeroWidth--) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [getZeroAsc()](#getZeroAsc--) | बेस तत्व की ऊँचाई (बेसलाइन के ऊपर) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | बेस तत्व की ऊँचाई (बेसलाइन के ऊपर) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [getZeroDesc()](#getZeroDesc--) | बेस तत्व की गहराई (बेसलाइन के नीचे) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | बेस तत्व की गहराई (बेसलाइन के नीचे) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [getTransp()](#getTransp--) | वर्ग-आधारित स्पेसिंग नियमों के लिए फ़ैंटम को पारदर्शी माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
| [setTransp(boolean value)](#setTransp-boolean-) | वर्ग-आधारित स्पेसिंग नियमों के लिए फ़ैंटम को पारदर्शी माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```


बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब false होता है, तो बेस तत्व छिपा रहता है लेकिन अन्य फ़ैंटम सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML विशेषता m:show के अनुरूप है।

**Returns:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


बेस तत्व प्रदर्शित है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब false होता है, तो बेस तत्व छिपा रहता है लेकिन अन्य फ़ैंटम सेटिंग्स के आधार पर स्थान ले सकता है। यह OMML विशेषता m:show के अनुरूप है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML विशेषता m:zeroWid के अनुरूप है।

**Returns:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम अपने बेस के लिए क्षैतिज स्थान आरक्षित नहीं करता। यह OMML विशेषता m:zeroWid के अनुरूप है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


बेस तत्व की ऊँचाई (बेसलाइन के ऊपर) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को ऊँचा नहीं करता। यह OMML विशेषता m:zeroAsc के अनुरूप है।

**Returns:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


बेस तत्व की ऊँचाई (बेसलाइन के ऊपर) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को ऊँचा नहीं करता। यह OMML विशेषता m:zeroAsc के अनुरूप है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


बेस तत्व की गहराई (बेसलाइन के नीचे) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नीचे नहीं करता। यह OMML विशेषता m:zeroDesc के अनुरूप है।

**Returns:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


बेस तत्व की गहराई (बेसलाइन के नीचे) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम आसपास की गणितीय लाइन की बेसलाइन को नीचे नहीं करता। यह OMML विशेषता m:zeroDesc के अनुरूप है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


फ़ैंटम वर्ग-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम के भीतर के ऑपरेटर और प्रतीक अभी भी फ़ैंटम के आसपास गणितीय स्पेसिंग को प्रभावित करते हैं (जैसे कि प्रदर्शित हो)। जब false होता है, तो वर्ग-आधारित स्पेसिंग अनदेखा किया जाता है। यह OMML विशेषता m:transp के अनुरूप है।

**Returns:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


फ़ैंटम वर्ग-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं, यह दर्शाने वाले मान को प्राप्त या सेट करता है।

--------------------

जब true होता है, तो फ़ैंटम के भीतर के ऑपरेटर और प्रतीक अभी भी फ़ैंटम के आसपास गणितीय स्पेसिंग को प्रभावित करते हैं (जैसे कि प्रदर्शित हो)। जब false होता है, तो वर्ग-आधारित स्पेसिंग अनदेखा किया जाता है। यह OMML विशेषता m:transp के अनुरूप है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |