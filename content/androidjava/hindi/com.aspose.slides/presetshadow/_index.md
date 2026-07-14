---
title: PresetShadow
second_title: Aspose.Slides for Android जावा API रेफ़रेंस के द्वारा
description: एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/presetshadow/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | छाया की दिशा। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा। |
| [getDistance()](#getDistance--) | छाया की दूरी। |
| [setDistance(double value)](#setDistance-double-) | छाया की दूरी। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getPreset()](#getPreset--) | प्रीसेट। |
| [setPreset(int value)](#setPreset-int-) | प्रीसेट। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी प्रीसेट शैडो प्रभाव डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [PresetShadow](../../com.aspose.slides/presetshadow) वर्तमान [PresetShadow](../../com.aspose.slides/presetshadow) के बराबर है। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

छाया की दिशा। पढ़ें/लिखें  float .

**वापसी:**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

छाया की दिशा। पढ़ें/लिखें  float .

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

छाया की दूरी। पढ़ें/लिखें  double .

**वापसी:**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

छाया की दूरी। पढ़ें/लिखें  double .

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

छाया का रंग। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

प्रीसेट। पढ़ें/लिखें [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**वापसी:**  
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

प्रीसेट। पढ़ें/लिखें [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

विरासत लागू करके प्रभावी प्रीसेट शैडो प्रभाव डेटा प्राप्त करता है।

**वापसी:**  
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - एक [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट वापस करता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**वापसी:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent वापस करता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [PresetShadow](../../com.aspose.slides/presetshadow) वर्तमान [PresetShadow](../../com.aspose.slides/presetshadow) के बराबर है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [PresetShadow](../../com.aspose.slides/presetshadow)। |

**वापसी:**  
boolean - यदि ऑब्जेक्ट समान हैं तो true; अन्यथा false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**  
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।