---
title: CellFormat
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एक तालिका सेल के स्वरूप को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/cellformat/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

एक तालिका सेल का स्वरूप दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | एक सेल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderLeft()](#getBorderLeft--) | एक बाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderTop()](#getBorderTop--) | एक शीर्ष बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderRight()](#getBorderRight--) | एक दाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderBottom()](#getBorderBottom--) | एक नीचे बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | एक शीर्ष-बाएँ से नीचे-दाएँ विकर्ण लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | एक नीचे-बाएँ से ऊपर-दाएँ विकर्ण लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत और तालिका शैलियों के साथ लागू प्रभावी तालिका सेल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है। |
| [getTransparency()](#getTransparency--) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**रिटर्न:**  
long

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

एक सेल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

एक बाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

एक शीर्ष बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

एक दाएँ बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

एक नीचे बॉर्डर लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

एक शीर्ष-बाएँ से नीचे-दाएँ विकर्ण लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

एक नीचे-बाएँ से ऊपर-दाएँ विकर्ण लाइन प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

विरासत और तालिका शैलियों के साथ लागू प्रभावी तालिका सेल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - एक [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata)।

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |