---
title: RowFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टेबल पंक्ति के फ़ॉर्मेट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/rowformat/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

टेबल पंक्ति की फ़ॉर्मेट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत और टेबल शैलियों को लागू करते हुए प्रभावी टेबल पंक्ति फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


विरासत और टेबल शैलियों को लागू करते हुए प्रभावी टेबल पंक्ति फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है।

--------------------

> ```
> यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी भराव स्वरूप प्राप्त करने का प्रदर्शन करता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग हमेशा पंक्ति फ़ॉर्मेटिंग से अधिक प्राथमिकता रखती है, पंक्ति - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक।
>  इसलिए अंततः CellFormatEffectiveData गुण हमेशा तालिका को ड्रॉ करने के लिए उपयोग किए जाते हैं। निम्नलिखित कोड केवल API का एक उदाहरण है।
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


**वापसी:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - एक [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata)।
### getVersion() {#getVersion--}
```
public final long getVersion()
```


संस्करण। केवल पढ़ने योग्य दीर्घ।

**वापसी:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


IPresentationComponent पैरेंट लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)