---
title: Effect
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एनीमेशन प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/effect/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

एनीमेशन प्रभाव का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getSequence()](#getSequence--) | एक प्रभाव के लिए अनुक्रम वापस करता है। |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation केवल-पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation)। |
| [getPresetClassType()](#getPresetClassType--) | प्रभाव के वर्ग को परिभाषित करता है। |
| [setPresetClassType(int value)](#setPresetClassType-int-) | प्रभाव के वर्ग को परिभाषित करता है। |
| [getType()](#getType--) | प्रभाव के प्रकार को परिभाषित करता है। |
| [setType(int value)](#setType-int-) | प्रभाव के प्रकार को परिभाषित करता है। |
| [getSubtype()](#getSubtype--) | प्रभाव के उपप्रकार को परिभाषित करता है। |
| [setSubtype(int value)](#setSubtype-int-) | प्रभाव के उपप्रकार को परिभाषित करता है। |
| [getBehaviors()](#getBehaviors--) | प्रभाव के लिए व्यवहार का संग्रह वापस करता है। |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | प्रभाव के लिए व्यवहार का संग्रह वापस करता है। |
| [getTiming()](#getTiming--) | प्रभाव के लिए टाइमिंग मान को परिभाषित करता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | प्रभाव के लिए टाइमिंग मान को परिभाषित करता है। |
| [getTargetShape()](#getTargetShape--) | प्रभाव के लिए लक्ष्य आकार वापस करता है। |
| [getSound()](#getSound--) | प्रभाव के लिए एम्बेडेड ध्वनि को परिभाषित किया गया। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | प्रभाव के लिए एम्बेडेड ध्वनि को परिभाषित किया गया। |
| [getStopPreviousSound()](#getStopPreviousSound--) | यह गुण निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले ध्वनि को रोकता है या नहीं। |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | यह गुण निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले ध्वनि को रोकता है या नहीं। |
| [getAfterAnimationType()](#getAfterAnimationType--) | प्रभाव के लिए बाद में एनीमेशन प्रकार को परिभाषित करता है। |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | प्रभाव के लिए बाद में एनीमेशन प्रकार को परिभाषित करता है। |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | प्रभाव के लिए बाद में एनीमेशन रंग को परिभाषित करता है। |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | प्रभाव के लिए बाद में एनीमेशन रंग को परिभाषित करता है। |
| [getAnimateTextType()](#getAnimateTextType--) | प्रभाव के लिए एनिमेट टेक्स्ट प्रकार को परिभाषित करता है। |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | प्रभाव के लिए एनिमेट टेक्स्ट प्रकार को परिभाषित करता है। |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | एनिमेटेड टेक्स्ट हिस्सों (शब्द या अक्षर) के बीच विलंब को परिभाषित करता है। |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | एनिमेटेड टेक्स्ट हिस्सों (शब्द या अक्षर) के बीच विलंब को परिभाषित करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

एक प्रभाव के लिए अनुक्रम वापस करता है। केवल-पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence).

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation केवल-पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation).

**रिटर्न:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

प्रभाव के वर्ग को परिभाषित करता है। पढ़ें/लिखें [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**रिटर्न:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

प्रभाव के वर्ग को परिभाषित करता है। पढ़ें/लिखें [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```

प्रभाव के प्रकार को परिभाषित करता है। पढ़ें/लिखें [EffectType](../../com.aspose.slides/effecttype).

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

प्रभाव के प्रकार को परिभाषित करता है। पढ़ें/लिखें [EffectType](../../com.aspose.slides/effecttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

प्रभाव के उपप्रकार को परिभाषित करता है। पढ़ें/लिखें [EffectSubtype](../../com.aspose.slides/effectsubtype).

**रिटर्न:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

प्रभाव के उपप्रकार को परिभाषित करता है। पढ़ें/लिखें [EffectSubtype](../../com.aspose.slides/effectsubtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

एक प्रभाव के लिए व्यवहार का संग्रह वापस करता है। पढ़ें/लिखें [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**रिटर्न:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

एक प्रभाव के लिए व्यवहार का संग्रह वापस करता है। पढ़ें/लिखें [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

प्रभाव के लिए टाइमिंग मान को परिभाषित करता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**रिटर्न:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

प्रभाव के लिए टाइमिंग मान को परिभाषित करता है। पढ़ें/लिखें [ITiming](../../com.aspose.slides/itiming).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

एक प्रभाव के लिए लक्ष्य आकार वापस करता है। केवल-पढ़ने योग्य [IShape](../../com.aspose.slides/ishape).

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

एक प्रभाव के लिए एम्बेडेड ध्वनि को परिभाषित किया गया। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए प्रभाव अनुक्रम प्राप्त करता है
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // प्रभाव ध्वनि को बाइट एरे में निकालता है
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

एक प्रभाव के लिए एम्बेडेड ध्वनि को परिभाषित किया गया। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए प्रभाव अनुक्रम प्राप्त करता है
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // प्रभाव ध्वनि को बाइट एरे में निकालता है
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

यह गुण निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले ध्वनि को रोकता है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरी स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे प्रभाव की Enhancements/Sound को "Stop Previous Sound" में बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

यह गुण निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले ध्वनि को रोकता है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरी स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे प्रभाव की Enhancements/Sound को "Stop Previous Sound" में बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

एक प्रभाव के लिए बाद में एनीमेशन प्रकार को परिभाषित करता है। पढ़ें/लिखें [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के After animation को "Hide on Next Mouse Click" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

एक प्रभाव के लिए बाद में एनीमेशन प्रकार को परिभाषित करता है। पढ़ें/लिखें [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के After animation को "Hide on Next Mouse Click" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

एक प्रभाव के लिए बाद में एनीमेशन रंग को परिभाषित करता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के After animation प्रकार को "Color" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // प्रभाव के After animation रंग को सेट करें।
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

एक प्रभाव के लिए बाद में एनीमेशन रंग को परिभाषित करता है। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के After animation प्रकार को "Color" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // प्रभाव के After animation रंग को सेट करें।
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

एक प्रभाव के लिए एनिमेट टेक्स्ट प्रकार को परिभाषित करता है। आकार का टेक्स्ट अक्षर, शब्द या सभी को एक साथ एनिमेट किया जा सकता है। पढ़ें/लिखें  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के Animate text प्रकार को "By letter" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

एक प्रभाव के लिए एनिमेट टेक्स्ट प्रकार को परिभाषित करता है। आकार का टेक्स्ट अक्षर, शब्द या सभी को एक साथ एनिमेट किया जा सकता है। पढ़ें/लिखें  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के Animate text प्रकार को "By letter" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

एनिमेटेड टेक्स्ट हिस्सों (शब्द या अक्षर) के बीच विलंब को परिभाषित करता है। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत दर्शाता है। एक नकारात्मक मान सेकंड में विलंब दर्शाता है। पढ़ें/लिखें  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के Animate text प्रकार को "By word" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनीमेटेड टेक्स्ट भागों (शब्दों) के बीच विलंब को प्रभाव अवधि का 20% सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

एनिमेटेड टेक्स्ट हिस्सों (शब्द या अक्षर) के बीच विलंब को परिभाषित करता है। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत दर्शाता है। एक नकारात्मक मान सेकंड में विलंब दर्शाता है। पढ़ें/लिखें  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के पहले प्रभाव को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव के Animate text प्रकार को "By word" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनीमेटेड टेक्स्ट भागों (शब्द) के बीच विलंब को प्रभाव अवधि का 20% सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट वापस करता है। केवल-पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject