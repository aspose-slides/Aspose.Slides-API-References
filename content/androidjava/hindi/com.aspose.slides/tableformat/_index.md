---
title: TableFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टेबल का प्रारूप दर्शाता है।
type: docs
url: /hi/com.aspose.slides/tableformat/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफेस:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

टेबल के प्रारूप का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | टेबल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getTransparency()](#getTransparency--) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | इनहेरिटेंस और टेबल स्टाइल्स लागू किए हुए प्रभावी टेबल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

टेबल फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य  float .

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

इनहेरिटेंस और टेबल स्टाइल्स लागू किए हुए प्रभावी टेबल फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है।

--------------------

> ```
> यह उदाहरण विभिन्न टेबल लॉजिक भागों के लिए प्रभावी फ़िल फ़ॉर्मेट प्राप्त करने को दर्शाता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग की प्राथमिकता हमेशा रो फ़ॉर्मेटिंग से अधिक होती है, रो - कॉलम से अधिक, कॉलम - संपूर्ण टेबल से अधिक।
>  इसलिए अंततः CellFormatEffectiveData प्रॉपर्टीज़ का उपयोग टेबल को ड्रॉ करने के लिए किया जाता है। निम्नलिखित कोड केवल API का एक उदाहरण है।
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - एक [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata)।
### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Parent IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)