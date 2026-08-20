---
title: IColorFormat
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icolorformat/
---
**सब लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

एक प्रस्तुति में उपयोग किए जाने वाले रंग को दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getColorType()](#getColorType--) | रंग परिभाषा विधि को लौटाता है या सेट करता है। |
| [setColorType(int value)](#setColorType-int-) | रंग परिभाषा विधि को लौटाता है या सेट करता है। |
| [getColor()](#getColor--) | परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। |
| [setColor(Color value)](#setColor-java.awt.Color-) | परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। |
| [getPresetColor()](#getPresetColor--) | रंग पूर्वनिर्धारित को लौटाता है या सेट करता है। |
| [setPresetColor(int value)](#setPresetColor-int-) | रंग पूर्वनिर्धारित को लौटाता है या सेट करता है। |
| [getSystemColor()](#getSystemColor--) | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। |
| [setSystemColor(int value)](#setSystemColor-int-) | सिस्टम रंग तालिका द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। |
| [getSchemeColor()](#getSchemeColor--) | रंग योजना द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। |
| [setSchemeColor(int value)](#setSchemeColor-int-) | रंग योजना द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। |
| [getR()](#getR--) | एक रंग के लाल घटक को लौटाता है या सेट करता है। |
| [setR(byte value)](#setR-byte-) | एक रंग के लाल घटक को लौटाता है या सेट करता है। |
| [getG()](#getG--) | एक रंग के हरे घटक को लौटाता है या सेट करता है। |
| [setG(byte value)](#setG-byte-) | एक रंग के हरे घटक को लौटाता है या सेट करता है। |
| [getB()](#getB--) | एक रंग के नीले घटक को लौटाता है या सेट करता है। |
| [setB(byte value)](#setB-byte-) | एक रंग के नीले घटक को लौटाता है या सेट करता है। |
| [getFloatR()](#getFloatR--) | एक रंग के लाल घटक को लौटाता है या सेट करता है। |
| [setFloatR(float value)](#setFloatR-float-) | एक रंग के लाल घटक को लौटाता है या सेट करता है। |
| [getFloatG()](#getFloatG--) | एक रंग के हरे घटक को लौटाता है या सेट करता है। |
| [setFloatG(float value)](#setFloatG-float-) | एक रंग के हरे घटक को लौटाता है या सेट करता है। |
| [getFloatB()](#getFloatB--) | एक रंग के नीले घटक को लौटाता है या सेट करता है। |
| [setFloatB(float value)](#setFloatB-float-) | एक रंग के नीले घटक को लौटाता है या सेट करता है। |
| [getHue()](#getHue--) | HSL प्रतिनिधित्व में एक रंग के ह्यू घटक को लौटाता है या सेट करता है। |
| [setHue(float value)](#setHue-float-) | HSL प्रतिनिधित्व में एक रंग के ह्यू घटक को लौटाता है या सेट करता है। |
| [getSaturation()](#getSaturation--) | HSL प्रतिनिधित्व में एक रंग के संतृप्ति घटक को लौटाता है या सेट करता है। |
| [setSaturation(float value)](#setSaturation-float-) | HSL प्रतिनिधित्व में एक रंग के संतृप्ति घटक को लौटाता है या सेट करता है। |
| [getLuminance()](#getLuminance--) | HSL प्रतिनिधित्व में एक रंग के चमक घटक को लौटाता है या सेट करता है। |
| [setLuminance(float value)](#setLuminance-float-) | HSL प्रतिनिधित्व में एक रंग के चमक घटक को लौटाता है या सेट करता है। |
| [getColorTransform()](#getColorTransform--) | एक रंग पर लागू किए गए रंग रूपांतरणों का संग्रह लौटाता है। |
| [toString(int format)](#toString-int-) | एक स्ट्रिंग लौटाता है जो वर्तमान रंग प्रारूप का प्रतिनिधित्व करती है। |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | रंग स्वरूप को "color" से कॉपी करें। |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

रंग परिभाषा विधि को लौटाता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**वापसी:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

रंग परिभाषा विधि को लौटाता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। RGB रंग सेट करता है और सभी रंग रूपांतरण साफ़ करता है। पढ़ें/लिखें java.awt.Color।

**वापसी:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

परिणामी रंग लौटाता है (सभी रंग रूपांतरण लागू किए हुए)। RGB रंग सेट करता है और सभी रंग रूपांतरण साफ़ करता है। पढ़ें/लिखें java.awt.Color।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

रंग पूर्वनिर्धारित को लौटाता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**वापसी:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

रंग पूर्वनिर्धारित को लौटाता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**वापसी:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

रंग योजना द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**वापसी:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

रंग योजना द्वारा पहचाने गए रंग को लौटाता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

एक रंग के लाल घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

एक रंग के लाल घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

एक रंग के हरे घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

एक रंग के हरे घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

एक रंग के नीले घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**वापसी:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

एक रंग के नीले घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें byte।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

एक रंग के लाल घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

एक रंग के लाल घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

एक रंग के हरे घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

एक रंग के हरे घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

एक रंग के नीले घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

एक रंग के नीले घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL प्रतिनिधित्व में एक रंग के ह्यू घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL प्रतिनिधित्व में एक रंग के ह्यू घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL प्रतिनिधित्व में एक रंग के संतृप्ति घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL प्रतिनिधित्व में एक रंग के संतृप्ति घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL प्रतिनिधित्व में एक रंग के चमक घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**वापसी:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL प्रतिनिधित्व में एक रंग के चमक घटक को लौटाता है या सेट करता है। सभी रंग रूपांतरण अनदेखा किए जाते हैं। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

एक रंग पर लागू किए गए रंग रूपांतरणों का संग्रह लौटाता है। केवल-पढ़नेयोग्य [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)।

**वापसी:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

एक स्ट्रिंग लौटाता है जो वर्तमान रंग प्रारूप का प्रतिनिधित्व करती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | int | रंग स्ट्रिंग प्रारूप का प्रकार। |

**वापसी:**
java.lang.String - एक स्ट्रिंग जो वर्तमान रंग प्रारूप का प्रतिनिधित्व करती है।
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

रंग स्वरूप को "color" से कॉपी करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |