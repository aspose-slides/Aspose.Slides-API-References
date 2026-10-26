---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API संदर्भ
description: पाठ एनीमेशन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

पाठ एनीमेशन का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | वर्तमान क्रम के अंत में नया प्रभाव समूह पाठ एनीमेशन के अंत में जोड़ें। |
| [getBuildType()](#getBuildType--) | निर्माण प्रकार की सूची (उदाहरण के लिए |
| [setBuildType(int value)](#setBuildType-int-) | निर्माण प्रकार की सूची (उदाहरण के लिए |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | समूह के साथ या बिना (null) लिंक्ड शेप प्रभाव Read/write [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | समूह के साथ या बिना (null) लिंक्ड शेप प्रभाव Read/write [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

वर्तमान क्रम के अंत में नया प्रभाव समूह पाठ एनीमेशन के अंत में जोड़ें। यह केवल तब मान्य है जब टेक्स्ट पैराग्राफों की गिनती इस समूह के प्रभावों की गिनती के बराबर या अधिक हो!

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| effectType | int | एनिमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न्स:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

टेक्स्ट एनीमेशन के निर्माण प्रकार की सूची (उदाहरण के लिए पैराग्राफ 1,2,3, सभी एक साथ) Read/write \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**रिटर्न्स:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

टेक्स्ट एनीमेशन के निर्माण प्रकार की सूची (उदाहरण के लिए पैराग्राफ 1,2,3, सभी एक साथ) Read/write \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

समूह के साथ या बिना (null) लिंक्ड शेप प्रभाव Read/write [IEffect](../../com.aspose.slides/ieffect).

**रिटर्न्स:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

समूह के साथ या बिना (null) लिंक्ड शेप प्रभाव Read/write [IEffect](../../com.aspose.slides/ieffect).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |