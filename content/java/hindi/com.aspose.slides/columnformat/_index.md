---
title: ColumnFormat
second_title: Aspose.Slides for Java API रेफ़रेंस
description: टेबल कॉलम का प्रारूप दर्शाता है।
type: docs
url: /hi/com.aspose.slides/columnformat/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

टेबल कॉलम के प्रारूप का प्रतिनिधित्व करता है।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत और टेबल शैलियों लागू होने के साथ प्रभावी टेबल कॉलम फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

विरासत और टेबल शैलियों लागू होने के साथ प्रभावी टेबल कॉलम फ़ॉर्मेटिंग प्रॉपर्टीज़ प्राप्त करता है।

--------------------

> ```
> यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी फ़िल फ़ॉर्मेट प्राप्त करने को दर्शाता है।
>  कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग का हमेशा पंक्ति फ़ॉर्मेटिंग से अधिक प्राथमिकता होती है, पंक्ति - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक।
>  अतः अंत में CellFormatEffectiveData गुणों का हमेशा तालिका को ड्रॉ करने के लिए उपयोग किया जाता है। नीचे दिया गया कोड केवल API का एक उदाहरण है।
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


**रिटर्न मान:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - एक [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. केवल-पढ़ने योग्य long.

**रिटर्न मान:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

वापस देता है parent IPresentationComponent. केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**रिटर्न मान:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)