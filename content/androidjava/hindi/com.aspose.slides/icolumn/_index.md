---
title: IColumn
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक तालिका में एक कॉलम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icolumn/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

एक तालिका में एक कॉलम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getColumnFormat()](#getColumnFormat--) | इस कॉलम के लिए फ़ॉर्मेटिंग प्रॉपर्टी शामिल करने वाला ColumnFormat ऑब्जेक्ट लौटाता है। |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

इस कॉलम के लिए फ़ॉर्मेटिंग प्रॉपर्टी शामिल करने वाला ColumnFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IColumnFormat](../../com.aspose.slides/icolumnformat)।

**वापसी:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)