---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /hi/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग गुणों को शामिल करता है।

--------------------

यह इंटरफ़ेस [ITextFrameFormat](../../com.aspose.slides/itextframeformat) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू होने के साथ प्रभावी फ़ॉर्मेटिंग मान वापस किए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | प्रभावी टेक्स्ट की शैली को लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बायाँ मार्जिन (पॉइंट) लौटाता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दायां मार्जिन (पॉइंट) लौटाता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर का मार्जिन (पॉइंट) लौटाता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे का मार्जिन (पॉइंट) लौटाता है। |
| [getWrapText()](#getWrapText--) | टेक्स्ट को TextFrame की मार्जिन पर रैप किया गया है या नहीं लौटाता है। |
| [getAnchoringType()](#getAnchoringType--) | TextFrame में वर्टिकल एंकर टेक्स्ट लौटाता है। |
| [getCenterText()](#getCenterText--) | टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए या नहीं लौटाता है। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट की अभिविन्यास लौटाता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट ऑटोफिट मोड लौटाता है। |
| [getColumnCount()](#getColumnCount--) | बाउंडिंग रेक्टेंगल में टेक्स्ट की कॉलम संख्या निर्दिष्ट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट में) निर्दिष्ट करता है। |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


प्रभावी टेक्स्ट की शैली को लौटाता है। केवल-पढ़ने योग्य [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)।

**वापसी:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


TextFrame में बायाँ मार्जिन (पॉइंट) लौटाता है। केवल-पढ़ने योग्य double।

**वापसी:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


TextFrame में दायां मार्जिन (पॉइंट) लौटाता है। केवल-पढ़ने योग्य double।

**वापसी:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


TextFrame में ऊपर का मार्जिन (पॉइंट) लौटाता है। केवल-पढ़ने योग्य double।

**वापसी:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


TextFrame में नीचे का मार्जिन (पॉइंट) लौटाता है। केवल-पढ़ने योग्य double।

**वापसी:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


टेक्स्ट को TextFrame की मार्जिन पर रैप किया गया है या नहीं लौटाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


TextFrame में वर्टिकल एंकर टेक्स्ट लौटाता है। केवल-पढ़ने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype)।

**वापसी:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए या नहीं लौटाता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


टेक्स्ट की अभिविन्यास लौटाता है। केवल-पढ़ने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**वापसी:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


टेक्स्ट ऑटोफिट मोड लौटाता है। केवल-पढ़ने योग्य [TextAutofitType](../../com.aspose.slides/textautofittype)।

**वापसी:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


बाउंडिंग रेक्टेंगल में टेक्स्ट की कॉलम संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट में) निर्दिष्ट करता है। केवल-पढ़ने योग्य float।

**वापसी:**
float