---
title: IColorFormat
second_title: Aspose.Slides for Android, Java API संदर्भ
description: एक प्रस्तुति में उपयोग किए गए रंग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icolorformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

एक प्रस्तुति में उपयोग किए गए रंग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColorType()](#getColorType--) | रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। |
| [setColorType(int value)](#setColorType-int-) | रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। |
| [getColor()](#getColor--) | परिणामी रंग को लौटाता है (सभी रंग परिवर्तन लागू किए गए)। |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | परिणामी रंग को लौटाता है (सभी रंग परिवर्तन लागू किए गए)। |
| [getPresetColor()](#getPresetColor--) | रंग पूर्वनिर्धारित को प्राप्त करता है या सेट करता है। |
| [setPresetColor(int value)](#setPresetColor-int-) | रंग पूर्वनिर्धारित को प्राप्त करता है या सेट करता है। |
| [getSystemColor()](#getSystemColor--) | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। |
| [setSystemColor(int value)](#setSystemColor-int-) | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। |
| [getSchemeColor()](#getSchemeColor--) | रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। |
| [setSchemeColor(int value)](#setSchemeColor-int-) | रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। |
| [getR()](#getR--) | रंग के लाल घटक को प्राप्त करता है या सेट करता है। |
| [setR(byte value)](#setR-byte-) | रंग के लाल घटक को प्राप्त करता है या सेट करता है। |
| [getG()](#getG--) | रंग के हरे घटक को प्राप्त करता है या सेट करता है। |
| [setG(byte value)](#setG-byte-) | रंग के हरे घटक को प्राप्त करता है या सेट करता है। |
| [getB()](#getB--) | रंग के नीले घटक को प्राप्त करता है या सेट करता है। |
| [setB(byte value)](#setB-byte-) | रंग के नीले घटक को प्राप्त करता है या सेट करता है। |
| [getFloatR()](#getFloatR--) | रंग के लाल घटक को प्राप्त करता है या सेट करता है। |
| [setFloatR(float value)](#setFloatR-float-) | रंग के लाल घटक को प्राप्त करता है या सेट करता है। |
| [getFloatG()](#getFloatG--) | रंग के हरे घटक को प्राप्त करता है या सेट करता है। |
| [setFloatG(float value)](#setFloatG-float-) | रंग के हरे घटक को प्राप्त करता है या सेट करता है। |
| [getFloatB()](#getFloatB--) | रंग के नीले घटक को प्राप्त करता है या सेट करता है। |
| [setFloatB(float value)](#setFloatB-float-) | रंग के नीले घटक को प्राप्त करता है या सेट करता है। |
| [getHue()](#getHue--) | HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। |
| [setHue(float value)](#setHue-float-) | HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। |
| [getSaturation()](#getSaturation--) | HSL प्रतिनिधित्व में रंग के संतृप्ति घटक को प्राप्त करता है या सेट करता है। |
| [setSaturation(float value)](#setSaturation-float-) | HSL प्रतिनिधित्व में रंग के संतृप्ति घटक को प्राप्त करता है या सेट करता है। |
| [getLuminance()](#getLuminance--) | HSL प्रतिनिधित्व में रंग के प्रकाशता घटक को प्राप्त करता है या सेट करता है। |
| [setLuminance(float value)](#setLuminance-float-) | HSL प्रतिनिधित्व में रंग के प्रकाशता घटक को प्राप्त करता है या सेट करता है। |
| [getColorTransform()](#getColorTransform--) | रंग पर लागू किए गए रंग परिवर्तन संग्रह को लौटाता है। |
| [toString(int format)](#toString-int-) | एक String लौटाता है जो वर्तमान रंग स्वरूप का प्रतिनिधित्व करता है। |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color" से रंग स्वरूप कॉपी करें। |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**वापसी:**  
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

परिणामी रंग को लौटाता है (सभी रंग परिवर्तन लागू किए गए)। RGB रंग सेट करता है और सभी रंग परिवर्तन साफ़ करता है। पढ़ें/लिखें java.lang.Integer।

**वापसी:**  
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

परिणामी रंग को लौटाता है (सभी रंग परिवर्तन लागू किए गए)। RGB रंग सेट करता है और सभी रंग परिवर्तन साफ़ करता है। पढ़ें/लिखें java.lang.Integer।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

रंग पूर्वनिर्धारित को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**वापसी:**  
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

रंग पूर्वनिर्धारित को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**वापसी:**  
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**वापसी:**  
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**  
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**  
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**  
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें byte।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL प्रतिनिधित्व में रंग के संतृप्ति घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL प्रतिनिधित्व में रंग के संतृप्ति घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL प्रतिनिधित्व में रंग के प्रकाशता घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**  
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL प्रतिनिधित्व में रंग के प्रकाशता घटक को प्राप्त करता है या सेट करता है। सभी रंग परिवर्तन नज़रअंदाज़ किए जाते हैं। पढ़ें/लिखें float।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

रंग पर लागू किए गए रंग परिवर्तन संग्रह को लौटाता है। केवल-पढ़ने योग्य [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)।

**वापसी:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

एक String लौटाता है जो वर्तमान रंग स्वरूप का प्रतिनिधित्व करता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | int | रंग स्ट्रिंग स्वरूप का प्रकार। |

**वापसी:**  
java.lang.String - एक स्ट्रिंग जो वर्तमान रंग स्वरूप का प्रतिनिधित्व करती है।
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

"color" से रंग स्वरूप कॉपी करें।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | रंग [IColorFormat](../../com.aspose.slides/icolorformat) |