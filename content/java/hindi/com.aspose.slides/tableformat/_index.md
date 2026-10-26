---
title: TableFormat
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: टेबल के प्रारूप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/tableformat/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

टेबल का फ़ॉर्मेट दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | टेबल फिल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। |
| [getTransparency()](#getTransparency--) | फ़िल रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | फ़िल रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत और टेबल शैलियों के लागू होने के साथ प्रभावी टेबल फ़ॉर्मेटिंग प्रॉपर्टीज़ को प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

टेबल फिल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

फ़िल रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

फ़िल रंग की पारदर्शिता को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

विरासत और टेबल शैलियों के लागू होने के साथ प्रभावी टेबल फ़ॉर्मेटिंग प्रॉपर्टीज़ को प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**वापसी:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**वापसी:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent को लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)