---
title: RowFormat
second_title: Aspose.Slides for Java API संदर्भ
description: तालिका पंक्ति के स्वरूप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/rowformat/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

तालिका पंक्ति के स्वरूप का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत और तालिका शैली लागू करके तालिका पंक्ति के प्रभावी स्वरूपण गुण प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


विरासत और तालिका शैली लागू करके तालिका पंक्ति के प्रभावी स्वरूपण गुण प्राप्त करता है।

--------------------

> ```
> यह उदाहरण विभिन्न तालिका लॉजिक भागों के लिए प्रभावी फिल फ़ॉर्मेट प्राप्त करने को दर्शाता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग हमेशा पंक्ति फ़ॉर्मेटिंग से अधिक प्राथमिकता रखती है, पंक्ति - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक।
>  इसलिए अन्ततः CellFormatEffectiveData गुण हमेशा तालिका को ड्रॉ करने के लिए उपयोग किए जाते हैं। नीचे दिया गया कोड केवल API का एक उदाहरण है।
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - A [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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


केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)