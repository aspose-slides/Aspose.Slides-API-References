---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: लाइन या स्टॉक-चार्ट की अप/डाउन बार तक पहुँच प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

लाइन या स्टॉक-चार्ट की अप/डाउन बार तक पहुँच प्रदान करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | अप बार का स्वरूप लौटाता है। |
| [getDownBarsFormat()](#getDownBarsFormat--) | डाउन बार का स्वरूप लौटाता है। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि चार्ट में अप/डाउन बार हैं या नहीं। |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | निर्धारित करता है कि चार्ट में अप/डाउन बार हैं या नहीं। |
| [getGapWidth()](#getGapWidth--) | गैप चौड़ाई लौटाता या सेट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | गैप चौड़ाई लौटाता या सेट करता है। |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

अप बार का स्वरूप लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

डाउन बार का स्वरूप लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

निर्धारित करता है कि चार्ट में अप/डाउन बार हैं या नहीं। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

निर्धारित करता है कि चार्ट में अप/डाउन बार हैं या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

गैप चौड़ाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

गैप चौड़ाई लौटाता या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |