---
title: TextAnimation
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: पाठ एनीमेशन को दर्शाता है।
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

पाठ एनीमेशन को दर्शाता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह पाठ एनीमेशन के अंत तक पहुँच सके। |
| [getBuildType()](#getBuildType--) | निर्माण प्रकार की सूची (उदाहरण के लिए |
| [setBuildType(int value)](#setBuildType-int-) | निर्माण प्रकार की सूची (उदाहरण के लिए |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | समूह के साथ या बिना (null) जुड़ी आकार प्रभाव। |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | समूह के साथ या बिना (null) जुड़ी आकार प्रभाव। |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


वर्तमान अनुक्रम के अंत में नया प्रभाव जोड़ें ताकि समूह पाठ एनीमेशन के अंत तक पहुँच सके। केवल तब मान्य जब पाठ अनुच्छेदों की संख्या इस समूह के प्रभावों की संख्या के बराबर या अधिक हो!

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी मान:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


पाठ एनीमेशन के निर्माण प्रकार की सूची (उदाहरण के लिए अनुच्छेद 1,2,3, सभी एक साथ)। पढ़ें/लिखें [BuildType](../../com.aspose.slides/buildtype)।

**वापसी मान:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


पाठ एनीमेशन के निर्माण प्रकार की सूची (उदाहरण के लिए अनुच्छेद 1,2,3, सभी एक साथ)। पढ़ें/लिखें [BuildType](../../com.aspose.slides/buildtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```java
public final IEffect getEffectAnimateBackgroundShape()
```


समूह के साथ या बिना (null) जुड़ी आकार प्रभाव। पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)।

**वापसी मान:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


समूह के साथ या बिना (null) जुड़ी आकार प्रभाव। पढ़ें/लिखें [IEffect](../../com.aspose.slides/ieffect)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |