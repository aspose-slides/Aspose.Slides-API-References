---
title: ColorFormat
second_title: Java के लिए Aspose.Slides API संदर्भ
description: प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/colorformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

एक प्रस्तुति में उपयोग किए जाने वाले रंग का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getColorType()](#getColorType--) | रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। |
| [setColorType(int value)](#setColorType-int-) | रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। |
| [getColor()](#getColor--) | परिणामी रंग को लौटाता है (सभी रंग रूपांतरण लागू होने के साथ)। |
| [setColor(Color value)](#setColor-java.awt.Color-) | परिणामी रंग को लौटाता है (सभी रंग रूपांतरण लागू होने के साथ)। |
| [getPresetColor()](#getPresetColor--) | रंग प्रीसेट को प्राप्त करता है या सेट करता है। |
| [setPresetColor(int value)](#setPresetColor-int-) | रंग प्रीसेट को प्राप्त करता है या सेट करता है। |
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
| [getSaturation()](#getSaturation--) | HSL प्रतिनिधित्व में रंग की संतृप्ति घटक को प्राप्त करता है या सेट करता है। |
| [setSaturation(float value)](#setSaturation-float-) | HSL प्रतिनिधित्व में रंग की संतृप्ति घटक को प्राप्त करता है या सेट करता है। |
| [getLuminance()](#getLuminance--) | HSL प्रतिनिधित्व में रंग की चमक घटक को प्राप्त करता है या सेट करता है। |
| [setLuminance(float value)](#setLuminance-float-) | HSL प्रतिनिधित्व में रंग की चमक घटक को प्राप्त करता है या सेट करता है। |
| [getColorTransform()](#getColorTransform--) | रंग पर लागू किए गए रंग रूपांतरणों का संग्रह लौटाता है। |
| [toString(int format)](#toString-int-) | एक स्ट्रिंग लौटाता है जो वर्तमान रंग स्वरूप का प्रतिनिधित्व करती है। |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color" से रंग स्वरूप कॉपी करें। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट वस्तु के साथ समानता की जाँच करता है। |
| [hashCode()](#hashCode--) | हैश कोड लौटाता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getColorType() {#getColorType--}
```
public final int getColorType()
```

रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**वापसी:**
int
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

रंग परिभाषा विधि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ColorType](../../com.aspose.slides/colortype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public final Color getColor()
```

परिणामी रंग को लौटाता है (सभी रंग रूपांतरण लागू होने के साथ)। RGB रंग सेट करता है और सभी रंग रूपांतरण साफ़ करता है। पढ़ें/लिखें java.awt.Color।

**वापसी:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

परिणामी रंग को लौटाता है (सभी रंग रूपांतरण लागू होने के साथ)। RGB रंग सेट करता है और सभी रंग रूपांतरण साफ़ करता है। पढ़ें/लिखें java.awt.Color।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

रंग प्रीसेट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**वापसी:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

रंग प्रीसेट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [PresetColor](../../com.aspose.slides/presetcolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**वापसी:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

सिस्टम रंग तालिका द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SystemColor](../../com.aspose.slides/systemcolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**वापसी:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

रंग योजना द्वारा पहचाने गए रंग को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [SchemeColor](../../com.aspose.slides/schemecolor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public final byte getR()
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  byte .

**वापसी:**
byte
### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  byte .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public final byte getG()
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं।

**वापसी:**
byte
### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public final byte getB()
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  byte .

**वापसी:**
byte
### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  byte .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

रंग के लाल घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

रंग के हरे घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

रंग के नीले घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public final float getHue()
```

HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

HSL प्रतिनिधित्व में रंग के ह्यू घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

HSL प्रतिनिधित्व में रंग की संतृप्ति घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

HSL प्रतिनिधित्व में रंग की संतृप्ति घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

HSL प्रतिनिधित्व में रंग की चमक घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**वापसी:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

HSL प्रतिनिधित्व में रंग की चमक घटक को प्राप्त करता है या सेट करता है। सभी रंग रूपांतरण अनदेखी किए जाते हैं। पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

रंग पर लागू किए गए रंग रूपांतरणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)।

**वापसी:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

वर्तमान रंग स्वरूप का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | int | रंग स्ट्रिंग स्वरूप का प्रकार। |

**वापसी:**
java.lang.String - एक स्ट्रिंग जो वर्तमान रंग स्वरूप का प्रतिनिधित्व करती है।
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

"color" से रंग स्वरूप कॉपी करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्दिष्ट वस्तु के साथ समानता की जाँच करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वस्तु। |

**वापसी:**
boolean - यदि वस्तुएँ समान हैं तो true, अन्यथा false।
### hashCode() {#hashCode--}
```
public int hashCode()
```

हैश कोड लौटाता है।

**वापसी:**
int - हैश कोड।
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**वापसी:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

पैरेंट IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)