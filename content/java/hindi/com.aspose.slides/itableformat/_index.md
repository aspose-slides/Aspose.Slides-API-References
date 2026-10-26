---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /hi/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

टेबल के स्वरूप का प्रतिनिधित्व करता है।
## Methods

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | एक टेबल फिल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getTransparency()](#getTransparency--) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [setTransparency(float value)](#setTransparency-float-) | फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत और लागू टेबल स्टाइल्स के साथ प्रभावी टेबल फ़ॉर्मैटिंग प्रॉपर्टीज़ प्राप्त करता है। |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


एक टेबल फिल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य  float ।

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


फ़िल रंग की पारदर्शिता प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


विरासत और लागू टेबल स्टाइल्स के साथ प्रभावी टेबल फ़ॉर्मैटिंग प्रॉपर्टीज़ प्राप्त करता है।

**रिटर्न:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - एक [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).