---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: एनीमेशन इफ़ेक्ट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ieffect/
---```
public interface IEffect
```

एनीमेशन इफ़ेक्ट को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSequence()](#getSequence--) | इफ़ेक्ट के लिए क्रम लौटाता है। |
| [getTextAnimation()](#getTextAnimation--) | पाठ एनीमेशन लौटाता है। |
| [getPresetClassType()](#getPresetClassType--) | इफ़ेक्ट का वर्ग परिभाषित करता है। |
| [setPresetClassType(int value)](#setPresetClassType-int-) | इफ़ेक्ट का वर्ग परिभाषित करता है। |
| [getType()](#getType--) | इफ़ेक्ट का प्रकार परिभाषित करता है। |
| [setType(int value)](#setType-int-) | इफ़ेक्ट का प्रकार परिभाषित करता है। |
| [getSubtype()](#getSubtype--) | इफ़ेक्ट का उपप्रकार परिभाषित करता है। |
| [setSubtype(int value)](#setSubtype-int-) | इफ़ेक्ट का उपप्रकार परिभाषित करता है। |
| [getBehaviors()](#getBehaviors--) | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। |
| [getTiming()](#getTiming--) | इफ़ेक्ट के लिए टाइमिंग मान निर्धारित करता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | इफ़ेक्ट के लिए टाइमिंग मान निर्धारित करता है। |
| [getTargetShape()](#getTargetShape--) | इफ़ेक्ट के लिए लक्ष्य आकार लौटाता है। |
| [getSound()](#getSound--) | इफ़ेक्ट के लिए एम्बेडेड ध्वनि परिभाषित की गई है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | इफ़ेक्ट के लिए एम्बेडेड ध्वनि परिभाषित की गई है। |
| [getStopPreviousSound()](#getStopPreviousSound--) | यह विशेषता बताती है कि एनीमेशन इफ़ेक्ट पूर्व ध्वनि को रोकता है या नहीं। |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | यह विशेषता बताती है कि एनीमेशन इफ़ेक्ट पूर्व ध्वनि को रोकता है या नहीं। |
| [getAfterAnimationType()](#getAfterAnimationType--) | इफ़ेक्ट के लिए एक बाद की एनीमेशन प्रकार परिभाषित किया गया है। |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | इफ़ेक्ट के लिए एक बाद की एनीमेशन प्रकार परिभाषित किया गया है। |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | इफ़ेक्ट के लिए एक बाद की एनीमेशन रंग परिभाषित किया गया है। |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | इफ़ेक्ट के लिए एक बाद की एनीमेशन रंग परिभाषित किया गया है। |
| [getAnimateTextType()](#getAnimateTextType--) | इफ़ेक्ट के लिए टेक्स्ट एनीमेट प्रकार निर्धारित करता है। |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | इफ़ेक्ट के लिए टेक्स्ट एनीमेट प्रकार निर्धारित करता है। |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


इफ़ेक्ट के लिए क्रम लौटाता है। केवल-पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence).

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


पाठ एनीमेशन लौटाता है। केवल-पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation).

**रिटर्न:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


इफ़ेक्ट का वर्ग परिभाषित करता है। पढ़ना/लिखना [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**रिटर्न:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


इफ़ेक्ट का वर्ग परिभाषित करता है। पढ़ना/लिखना [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


इफ़ेक्ट का प्रकार परिभाषित करता है। पढ़ना/लिखना [EffectType](../../com.aspose.slides/effecttype).

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


इफ़ेक्ट का प्रकार परिभाषित करता है। पढ़ना/लिखना [EffectType](../../com.aspose.slides/effecttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


इफ़ेक्ट का उपप्रकार परिभाषित करता है। पढ़ना/लिखना [EffectSubtype](../../com.aspose.slides/effectsubtype).

**रिटर्न:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


इफ़ेक्ट का उपप्रकार परिभाषित करता है। पढ़ना/लिखना [EffectSubtype](../../com.aspose.slides/effectsubtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। पढ़ना/लिखना [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**रिटर्न:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। पढ़ना/लिखना [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


इफ़ेक्ट के लिए टाइमिंग मान निर्धारित करता है। पढ़ना/लिखना [ITiming](../../com.aspose.slides/itiming).

**रिटर्न:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


इफ़ेक्ट के लिए टाइमिंग मान निर्धारित करता है। पढ़ना/लिखना [ITiming](../../com.aspose.slides/itiming).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


इफ़ेक्ट के लिए लक्ष्य आकार लौटाता है। केवल-पढ़ने योग्य [IShape](../../com.aspose.slides/ishape).

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


इफ़ेक्ट के लिए एम्बेडेड ध्वनि परिभाषित की गई है। पढ़ना/लिखना [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए इफ़ेक्ट क्रम प्राप्त करता है
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // इफ़ेक्ट ध्वनि को बाइट ऐरे में निकालता है
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
public abstract void setSound(IAudio value)
```


इफ़ेक्ट के लिए एम्बेडेड ध्वनि परिभाषित की गई है। पढ़ना/लिखना [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए इफ़ेक्ट क्रम प्राप्त करता है
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // इफ़ेक्ट ध्वनि को बाइट ऐरे में निकालता है
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
public abstract boolean getStopPreviousSound()
```


यह विशेषता बताती है कि एनीमेशन इफ़ेक्ट पूर्व ध्वनि को रोकता है या नहीं। पढ़ना/लिखना  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरी स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट के Enhancements/Sound को "Stop Previous Sound" पर बदलें
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
public abstract void setStopPreviousSound(boolean value)
```


यह विशेषता बताती है कि एनीमेशन इफ़ेक्ट पूर्व ध्वनि को रोकता है या नहीं। पढ़ना/लिखना  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरी स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट के Enhancements/Sound को "Stop Previous Sound" पर बदलें
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
public abstract int getAfterAnimationType()
```


इफ़ेक्ट के लिए एक बाद की एनीमेशन प्रकार परिभाषित किया गया है। पढ़ना/लिखना  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के After animation को "Hide on Next Mouse Click" पर बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


इफ़ेक्ट के लिए एक बाद की एनीमेशन प्रकार परिभाषित किया गया है। पढ़ना/लिखना  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के After animation को "Hide on Next Mouse Click" पर बदलें
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
public abstract IColorFormat getAfterAnimationColor()
```


इफ़ेक्ट के लिए एक बाद की एनीमेशन रंग परिभाषित किया गया है। पढ़ना/लिखना [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के After animation प्रकार को "Color" में बदलें
> 
>      // इफ़ेक्ट के After animation रंग को सेट करें।
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


इफ़ेक्ट के लिए एक बाद की एनीमेशन रंग परिभाषित किया गया है। पढ़ना/लिखना [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के After animation प्रकार को "Color" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // इफ़ेक्ट के After animation रंग को सेट करें।
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
public abstract int getAnimateTextType()
```


इफ़ेक्ट के लिए टेक्स्ट एनीमेट प्रकार निर्धारित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। पढ़ना/लिखना  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By letter" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


इफ़ेक्ट के लिए टेक्स्ट एनीमेट प्रकार निर्धारित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। पढ़ना/लिखना  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By letter" में बदलें
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
public abstract float getDelayBetweenTextParts()
```


एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। एक सकारात्मक मान इफ़ेक्ट अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। पढ़ना/लिखना  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By word" में बदलें
> 
>      // एनिमेटेड टेक्स्ट भागों के बीच देरी को इफ़ेक्ट अवधि का 20% सेट करें।
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनिमेटेड टेक्स्ट भागों के बीच देरी को इफ़ेक्ट अवधि का 20% सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी निर्धारित करता है। एक सकारात्मक मान इफ़ेक्ट अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। पढ़ना/लिखना  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहली स्लाइड के प्रथम इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By word" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनिमेटेड टेक्स्ट भागों के बीच देरी को इफ़ेक्ट अवधि का 20% सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
