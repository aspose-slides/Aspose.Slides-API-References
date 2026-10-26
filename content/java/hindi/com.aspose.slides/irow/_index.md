---
title: IRow
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक तालिका में एक पंक्ति को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/irow/
---
**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

एक तालिका में एक पंक्ति को दर्शाता है।

## विधियाँ

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | पंक्ति की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | पंक्ति की न्यूनतम संभावित ऊँचाई को लौटाता या सेट करता है। |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | पंक्ति की न्यूनतम संभावित ऊँचाई को लौटाता या सेट करता है। |
| [getRowFormat()](#getRowFormat--) | पंक्ति के लिए फ़ॉर्मेटिंग गुणों को शामिल करने वाले RowFormat ऑब्जेक्ट को लौटाता है। |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

पंक्ति की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double.

**रिटर्न:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

पंक्ति की न्यूनतम संभावित ऊँचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**  
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

पंक्ति की न्यूनतम संभावित ऊँचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

पंक्ति के लिए फ़ॉर्मेटिंग गुणों को शामिल करने वाले RowFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IRowFormat](../../com.aspose.slides/irowformat).

**रिटर्न:**  
[IRowFormat](../../com.aspose.slides/irowformat)