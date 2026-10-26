---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: पाठ एनीमेशन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

पाठ एनीमेशन का प्रतिनिधित्व करता है।

## Methods

| विधि | विवरण |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह टेक्स्ट एनीमेशन के अंत में हो। |
| [getBuildType()](#getBuildType--) | बिल्ड प्रकार की सूची (उदाहरण के लिए |
| [setBuildType(int value)](#setBuildType-int-) | बिल्ड प्रकार की सूची (उदाहरण के लिए |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | समूह के साथ या बिना (null) जुड़ा रूप प्रभाव पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)। |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | समूह के साथ या बिना (null) जुड़ा रूप प्रभाव पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)। |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह टेक्स्ट एनीमेशन के अंत में हो। यह केवल तभी मान्य है जब टेक्स्ट पैराग्राफों की संख्या इस समूह के प्रभावों की संख्या के बराबर या अधिक हो!

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| effectType | int | एनिमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

पाठ एनीमेशन के लिए बिल्ड प्रकार की सूची (उदाहरण के लिए पैराग्राफ 1,2,3, सभी एक साथ)। पढ़ें/लिखें \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**रिटर्न:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

पाठ एनीमेशन के लिए बिल्ड प्रकार की सूची (उदाहरण के लिए पैराग्राफ 1,2,3, सभी एक साथ)। पढ़ें/लिखें \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

समूह के साथ या बिना (null) जुड़ा रूप प्रभाव पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)।

**रिटर्न:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

समूह के साथ या बिना (null) जुड़ा रूप प्रभाव पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |