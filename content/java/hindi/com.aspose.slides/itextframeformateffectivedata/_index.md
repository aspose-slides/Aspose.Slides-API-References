---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले अपरिवर्तनीय ऑब्जेक्ट।
type: docs
url: /hi/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले अपरिवर्तनीय ऑब्जेक्ट।

--------------------

यह इंटरफ़ेस [ITextFrameFormat](../../com.aspose.slides/itextframeformat) इंटरफ़ेस के साथ उपयोग किया जाता है ताकि विरासत लागू किए गए प्रभावी फ़ॉर्मेटिंग मानों को लौटाया जा सके।
## Methods

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | प्रभावी टेक्स्ट की शैली को लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | टेक्स्टफ़्रेम में बाएं मार्जिन (पॉइंट) को लौटाता है। |
| [getMarginRight()](#getMarginRight--) | टेक्स्टफ़्रेम में दाएं मार्जिन (पॉइंट) को लौटाता है। |
| [getMarginTop()](#getMarginTop--) | टेक्स्टफ़्रेम में शीर्ष मार्जिन (पॉइंट) को लौटाता है। |
| [getMarginBottom()](#getMarginBottom--) | टेक्स्टफ़्रेम में नीचे मार्जिन (पॉइंट) को लौटाता है। |
| [getWrapText()](#getWrapText--) | टेक्स्टफ़्रेम के मार्जिन पर टेक्स्ट लिपटा है या नहीं, लौटाता है। |
| [getAnchoringType()](#getAnchoringType--) | टेक्स्टफ़्रेम में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है। |
| [getCenterText()](#getCenterText--) | बॉक्स में क्षैतिज रूप से टेक्स्ट को केंद्रित किया जाना चाहिए या नहीं, लौटाता है। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट अभिविन्यास को लौटाता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट ऑटोफिट मोड को लौटाता है। |
| [getColumnCount()](#getColumnCount--) | बाउंडिंग आयत में टेक्स्ट के कॉलम की संख्या निर्दिष्ट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच का अंतराल (पॉइंट में) निर्दिष्ट करता है। |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


प्रभावी टेक्स्ट की शैली को लौटाता है। केवल-पढ़ने योग्य [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**वापसी:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


टेक्स्टफ़्रेम में बाएं मार्जिन (पॉइंट) को लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


टेक्स्टफ़्रेम में दाएं मार्जिन (पॉइंट) को लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


टेक्स्टफ़्रेम में शीर्ष मार्जिन (पॉइंट) को लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


टेक्स्टफ़्रेम में नीचे मार्जिन (पॉइंट) को लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


टेक्स्टफ़्रेम के मार्जिन पर टेक्स्ट लिपटा है या नहीं, लौटाता है। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


टेक्स्टफ़्रेम में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है। केवल-पढ़ने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype).

**वापसी:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


बॉक्स में क्षैतिज रूप से टेक्स्ट को केंद्रित किया जाना चाहिए या नहीं, लौटाता है। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


टेक्स्ट अभिविन्यास को लौटाता है। केवल-पढ़ने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype).

**वापसी:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


टेक्स्ट ऑटोफिट मोड को लौटाता है। केवल-पढ़ने योग्य [TextAutofitType](../../com.aspose.slides/textautofittype).

**वापसी:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


बाउंडिंग आयत में टेक्स्ट के कॉलम की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच का अंतराल (पॉइंट में) निर्दिष्ट करता है। केवल-पढ़ने योग्य float.

**वापसी:**
float