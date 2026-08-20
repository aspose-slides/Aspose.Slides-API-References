---
title: CellFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक तालिका सेल के स्वरूप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/cellformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

टेबल सेल के फ़ॉर्मेट को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | सेल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderLeft()](#getBorderLeft--) | बायीं बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderTop()](#getBorderTop--) | ऊपरी बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderRight()](#getBorderRight--) | दाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderBottom()](#getBorderBottom--) | नीचे की बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | ऊपर-बाएँ से नीचे-दाएँ तक की डायगोनल लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | नीचे-बाएँ से ऊपर-दाएँ तक की डायगोनल लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत और टेबल शैलियों के लागू होने के साथ प्रभावी टेबल सेल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है। |
| [getTransparency()](#getTransparency--) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने-योग्य long.

**रिटर्न:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


सेल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


बायीं बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


ऊपरी बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


दाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


नीचे की बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


ऊपर-बाएँ से नीचे-दाएँ तक की डायगोनल लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


नीचे-बाएँ से ऊपर-दाएँ तक की डायगोनल लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


विरासत और टेबल शैलियों के लागू होने के साथ प्रभावी टेबल सेल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है।

--------------------

> ```
> यह उदाहरण अलग-अलग टेबल लॉजिक भागों के लिए प्रभावी फ़िल फ़ॉर्मेट प्राप्त करने को दर्शाता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग की हमेशा पंक्ति फ़ॉर्मेटिंग से अधिक प्राथमिकता होती है, पंक्ति - कॉलम से अधिक, कॉलम - पूरे टेबल से अधिक।
>  इसलिए अंत में CellFormatEffectiveData प्रॉपर्टीज़ हमेशा टेबल को ड्रॉ करने के लिए उपयोग की जाती हैं। निम्नलिखित कोड केवल API का एक उदाहरण है।
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - एक [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य  float .

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |