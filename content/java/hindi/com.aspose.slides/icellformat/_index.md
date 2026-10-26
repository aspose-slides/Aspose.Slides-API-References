---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: एक तालिका सेल का स्वरूप दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

एक तालिका सेल का स्वरूप दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | एक सेल भरने की गुण वस्तु लौटाता है। |
| [getBorderLeft()](#getBorderLeft--) | एक बाएँ बॉर्डर रेखा गुण वस्तु लौटाता है। |
| [getBorderTop()](#getBorderTop--) | एक शीर्ष बॉर्डर रेखा गुण वस्तु लौटाता है। |
| [getBorderRight()](#getBorderRight--) | एक दाएँ बॉर्डर रेखा गुण वस्तु लौटाता है। |
| [getBorderBottom()](#getBorderBottom--) | एक नीचे बॉर्डर रेखा गुण वस्तु लौटाता है। |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | एक शीर्ष-बाएँ से नीचे-दाएँ विकर्ण रेखा गुण वस्तु लौटाता है। |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | एक नीचे-बाएँ से ऊपर-दाएँ विकर्ण रेखा गुण वस्तु लौटाता है। |
| [getTransparency()](#getTransparency--) | भरने के रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | भरने के रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत और तालिका शैलियों के लागू होने पर प्रभावी तालिका सेल स्वरूपण गुण प्राप्त करता है। |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

एक सेल भरने की गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

एक बाएँ बॉर्डर रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

एक शीर्ष बॉर्डर रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

एक दाएँ बॉर्डर रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

एक नीचे बॉर्डर रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

एक शीर्ष-बाएँ से नीचे-दाएँ विकर्ण रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

एक नीचे-बाएँ से ऊपर-दाएँ विकर्ण रेखा गुण वस्तु लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

भरने के रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ें/लिखें  float .

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

भरने के रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

विरासत और तालिका शैलियों के लागू होने पर प्रभावी तालिका सेल स्वरूपण गुण प्राप्त करता है।

**रिटर्न:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - एक [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).