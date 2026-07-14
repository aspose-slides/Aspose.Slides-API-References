---
title: ColumnFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक टेबल कॉलम के फ़ॉर्मेट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/columnformat/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

टेबल कॉलम का फ़ॉर्मेट दर्शाता है।
## विधियां

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत और टेबल शैलियों लागू करके प्रभावी टेबल कॉलम फ़ॉर्मेटिंग गुण प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

विरासत और टेबल शैलियों लागू करके प्रभावी टेबल कॉलम फ़ॉर्मेटिंग गुण प्राप्त करता है।

--------------------

> ```
> यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी फ़िल फ़ॉर्मेट प्राप्त करने को दर्शाता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग हमेशा रो फ़ॉर्मेटिंग से उच्च प्राथमिकता रखती है, रो - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक।
>  अंततः CellFormatEffectiveData गुण हमेशा तालिका को ड्रॉ करने के लिए उपयोग किए जाते हैं। निम्न कोड केवल API का एक उदाहरण है।
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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


**वापसी:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - एक [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। पढ़ने-केवल long।

**वापसी:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

पैरेंट IPresentationComponent लौटाता है। पढ़ने-केवल [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)