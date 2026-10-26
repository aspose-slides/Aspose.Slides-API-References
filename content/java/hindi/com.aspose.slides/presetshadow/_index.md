---
title: PresetShadow
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/presetshadow/
---
**Inheritance:**  
विरासत: java.lang.Object

**All Implemented Interfaces:**  
सभी कार्यान्वित इंटरफ़ेस: [com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।

## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | छाया की दिशा। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा। |
| [getDistance()](#getDistance--) | छाया की दूरी। |
| [setDistance(double value)](#setDistance-double-) | छाया की दूरी। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getPreset()](#getPreset--) | प्रीसेट। |
| [setPreset(int value)](#setPreset-int-) | प्रीसेट। |
| [getEffective()](#getEffective--) | विरासत लागू किए गए प्रभावी प्रीसेट शैडो डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [PresetShadow](../../com.aspose.slides/presetshadow) वर्तमान [PresetShadow](../../com.aspose.slides/presetshadow) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के हैश फ़ंक्शन के रूप में कार्य करता है। |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

छाया की दिशा। पढ़ने/लिखने  float .

**Returns:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

छाया की दिशा। पढ़ने/लिखने  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

छाया की दूरी। पढ़ने/लिखने  double .

**Returns:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

छाया की दूरी। पढ़ने/लिखने  double .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

छाया का रंग। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

प्रीसेट। पढ़ने/लिखने [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**Returns:**
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

प्रीसेट। पढ़ने/लिखने [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

विरासत लागू किए गए प्रभावी प्रीसेट शैडो डेटा प्राप्त करता है।

**Returns:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**Returns:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**Returns:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

पेरेंट IPresentationComponent लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [PresetShadow](../../com.aspose.slides/presetshadow) वर्तमान [PresetShadow](../../com.aspose.slides/presetshadow) के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [PresetShadow](../../com.aspose.slides/presetshadow)। |

**Returns:**
boolean - यदि ऑब्जेक्ट समान हैं तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के हैश फ़ंक्शन के रूप में कार्य करता है।

**Returns:**
int - वर्तमान ऑब्जेक्ट का हैश कोड।