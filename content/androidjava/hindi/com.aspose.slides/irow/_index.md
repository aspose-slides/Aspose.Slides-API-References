---
title: IRow
second_title: Aspose.Slides for Android का Java API संदर्भ
description: एक तालिका में पंक्ति का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/irow/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

एक तालिका में पंक्ति का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeight()](#getHeight--) | एक पंक्ति की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | एक पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | एक पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। |
| [getRowFormat()](#getRowFormat--) | एक RowFormat ऑब्जेक्ट लौटाता है जिसमें इस पंक्ति के लिए फ़ॉर्मेटिंग गुण होते हैं। |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

एक पंक्ति की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

एक पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**वापसी:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

एक पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

एक RowFormat ऑब्जेक्ट लौटाता है जिसमें इस पंक्ति के लिए फ़ॉर्मेटिंग गुण होते हैं। केवल-पढ़ने योग्य [IRowFormat](../../com.aspose.slides/irowformat).

**वापसी:**
[IRowFormat](../../com.aspose.slides/irowformat)