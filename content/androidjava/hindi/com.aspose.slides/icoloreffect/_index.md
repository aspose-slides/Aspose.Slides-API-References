---
title: IColorEffect
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: एनीमेशन व्यवहार के लिए एक रंग प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icoloreffect/
---
**सभी लागू इंटरफ़ेसेस:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

एक एनिमेशन व्यवहार के लिए रंग प्रभाव का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFrom()](#getFrom--) | यह मान व्यवहार के प्रारंभिक रंग को निर्दिष्ट करने के लिए उपयोग किया जाता है। |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | यह मान व्यवहार के प्रारंभिक रंग को निर्दिष्ट करने के लिए उपयोग किया जाता है। |
| [getTo()](#getTo--) | एनीमेशन रंग परिवर्तन के लिए परिणामी रंग का वर्णन करता है। |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | एनीमेशन रंग परिवर्तन के लिए परिणामी रंग का वर्णन करता है। |
| [getBy()](#getBy--) | रंग एनीमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है। |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | रंग एनीमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है। |
| [getColorSpace()](#getColorSpace--) | व्यवहार का रंग स्थान दर्शाता है। |
| [setColorSpace(int value)](#setColorSpace-int-) | व्यवहार का रंग स्थान दर्शाता है। |
| [getDirection()](#getDirection--) | रंग चक्र के आसपास hue को चक्रित करने की दिशा निर्दिष्ट करता है। |
| [setDirection(int value)](#setDirection-int-) | रंग चक्र के आसपास hue को चक्रित करने की दिशा निर्दिष्ट करता है। |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

यह मान व्यवहार के प्रारंभिक रंग को निर्दिष्ट करने के लिए उपयोग किया जाता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

यह मान व्यवहार के प्रारंभिक रंग को निर्दिष्ट करने के लिए उपयोग किया जाता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

एनीमेशन रंग परिवर्तन के लिए परिणामी रंग का वर्णन करता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

एनीमेशन रंग परिवर्तन के लिए परिणामी रंग का वर्णन करता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

रंग एनीमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है। पढ़ें/लिखें [IColorOffset](../../com.aspose.slides/icoloroffset)।

**रिटर्न:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

रंग एनीमेशन के लिए सापेक्ष ऑफ़सेट मान का वर्णन करता है। पढ़ें/लिखें [IColorOffset](../../com.aspose.slides/icoloroffset)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

व्यवहार का रंग स्थान दर्शाता है। पढ़ें/लिखें [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))।

**रिटर्न:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

व्यवहार का रंग स्थान दर्शाता है। पढ़ें/लिखें [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

रंग चक्र के आसपास hue को चक्रित करने की दिशा निर्दिष्ट करता है। पढ़ें/लिखें [ColorDirection](../../com.aspose.slides/colordirection)।

**रिटर्न:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

रंग चक्र के आसपास hue को चक्रित करने की दिशा निर्दिष्ट करता है। पढ़ें/लिखें [ColorDirection](../../com.aspose.slides/colordirection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |