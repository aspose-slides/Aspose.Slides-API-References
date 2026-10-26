---
title: IUpDownBarsManager
second_title: Aspose.Slides एंड्रॉइड के लिए जावा एपीआई रेफ़रेंस के माध्यम से
description: Line- या Stock-चार्ट की up/down बार तक पहुँच प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Line- या Stock-चार्ट की up/down बार तक पहुँच प्रदान करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | उप बारों का फ़ॉर्मेट लौटाता है। |
| [getDownBarsFormat()](#getDownBarsFormat--) | डाउन बारों का फ़ॉर्मेट लौटाता है। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि क्या चार्ट में up/down बार हैं। |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | निर्धारित करता है कि क्या चार्ट में up/down बार हैं। |
| [getGapWidth()](#getGapWidth--) | गैप चौड़ाई लौटाता है या सेट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | गैप चौड़ाई लौटाता है या सेट करता है। |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

उप बारों का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

डाउन बारों का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

निर्धारित करता है कि क्या चार्ट में up/down बार हैं। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

निर्धारित करता है कि क्या चार्ट में up/down बार हैं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

गैप चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य इंट।

**रिटर्न:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

गैप चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य इंट।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |