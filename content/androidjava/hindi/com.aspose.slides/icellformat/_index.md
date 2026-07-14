---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: एक तालिका कोशिका के प्रारूप को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

एक तालिका कोशिका के प्रारूप को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | एक कोशिका भराव गुणों वस्तु को लौटाता है। |
| [getBorderLeft()](#getBorderLeft--) | बाएँ सीमा रेखा गुणों वस्तु को लौटाता है। |
| [getBorderTop()](#getBorderTop--) | ऊपर की सीमा रेखा गुणों वस्तु को लौटाता है। |
| [getBorderRight()](#getBorderRight--) | दाएँ सीमा रेखा गुणों वस्तु को लौटाता है। |
| [getBorderBottom()](#getBorderBottom--) | नीचे की सीमा रेखा गुणों वस्तु को लौटाता है। |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | ऊपर-बाएँ से नीचे-दाएँ विकर्ण रेखा गुणों वस्तु को लौटाता है। |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | नीचे-बाएँ से ऊपर-दाएँ विकर्ण रेखा गुणों वस्तु को लौटाता है। |
| [getTransparency()](#getTransparency--) | भराव रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | भराव रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत और तालिका शैलियों के लागू होने के साथ प्रभावी तालिका कोशिका स्वरूपण गुणों को प्राप्त करता है। |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

एक कोशिका भराव गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

बाएँ सीमा रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

ऊपर की सीमा रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

दाएँ सीमा रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

नीचे की सीमा रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

ऊपर-बाएँ से नीचे-दाएँ विकर्ण रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

नीचे-बाएँ से ऊपर-दाएँ विकर्ण रेखा गुणों वस्तु को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

भराव रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  float .

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

भराव रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

विरासत और तालिका शैलियों के लागू होने के साथ प्रभावी तालिका कोशिका स्वरूपण गुणों को प्राप्त करता है।

**रिटर्न:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).