---
title: IColumn
second_title: Java के लिए Aspose.Slides API संदर्भ
description: एक तालिका में कॉलम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icolumn/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

एक तालिका में कॉलम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | कॉलम की चौड़ाई को लौटाता है या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | कॉलम की चौड़ाई को लौटाता है या सेट करता है। |
| [getColumnFormat()](#getColumnFormat--) | इस कॉलम के लिए फ़ॉर्मेटिंग विशेषताओं को समाहित करने वाले ColumnFormat ऑब्जेक्ट को लौटाता है। |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

कॉलम की चौड़ाई को लौटाता है या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

कॉलम की चौड़ाई को लौटाता है या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

इस कॉलम के लिए फ़ॉर्मेटिंग विशेषताओं को समाहित करने वाले ColumnFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IColumnFormat](../../com.aspose.slides/icolumnformat)।

**रिटर्न:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)