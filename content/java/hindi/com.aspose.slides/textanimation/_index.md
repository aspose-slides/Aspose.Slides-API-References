---
title: TextAnimation
second_title: Aspose.Slides for Java API संदर्भ
description: टेक्स्ट एनीमेशन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/textanimation/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)  
```
public class TextAnimation implements ITextAnimation
```

टेक्स्ट एनीमेशन का प्रतिनिधित्व करता है।  
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह टेक्स्ट एनीमेशन के अंत में हो। |
| [getBuildType()](#getBuildType--) | बिल्ड प्रकार की सूची (उदाहरण के लिये |
| [setBuildType(int value)](#setBuildType-int-) | बिल्ड प्रकार की सूची (उदाहरण के लिये |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | समूह के साथ या बिना (null) जुड़ा हुआ आकार प्रभाव। |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | समूह के साथ या बिना (null) जुड़ा हुआ आकार प्रभाव। |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह टेक्स्ट एनीमेशन के अंत में हो। यह केवल तभी मान्य है जब टेक्स्ट पैराग्राफ की गिनती इस समूह के प्रभावों की गिनती के बराबर या अधिक हो!

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| effectType | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन इफ़ेक्ट के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | इफ़ेक्ट का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) - नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

टेक्स्ट एनीमेशन के बिल्ड प्रकार की सूची (उदाहरण के लिये पैराग्राफ 1,2,3, सभी एक साथ). पढ़ने/लिखने योग्य [BuildType](../../com.aspose.slides/buildtype)।

**रिटर्न:**  
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

टेक्स्ट एनीमेशन के बिल्ड प्रकार की सूची (उदाहरण के लिये पैराग्राफ 1,2,3, सभी एक साथ). पढ़ने/लिखने योग्य [BuildType](../../com.aspose.slides/buildtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

समूह के साथ या बिना (null) जुड़ा हुआ आकार प्रभाव। पढ़ने/लिखने योग्य [IEffect](../../com.aspose.slides/ieffect)।

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

समूह के साथ या बिना (null) जुड़ा हुआ आकार प्रभाव। पढ़ने/लिखने योग्य [IEffect](../../com.aspose.slides/ieffect)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |