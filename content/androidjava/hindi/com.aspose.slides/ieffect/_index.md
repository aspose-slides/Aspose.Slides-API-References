---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /hi/com.aspose.slides/ieffect/
---``` 
public interface IEffect
```

एनीमेशन प्रभाव का प्रतिनिधित्व करता है।
## Methods

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | प्रभाव के लिए एक क्रम लौटाता है। |
| [getTextAnimation()](#getTextAnimation--) | टेक्स्ट एनीमेशन लौटाता है। |
| [getPresetClassType()](#getPresetClassType--) | प्रभाव की क्लास निर्धारित करता है। |
| [setPresetClassType(int value)](#setPresetClassType-int-) | प्रभाव की क्लास निर्धारित करता है। |
| [getType()](#getType--) | प्रभाव का प्रकार निर्धारित करता है। |
| [setType(int value)](#setType-int-) | प्रभाव का प्रकार निर्धारित करता है। |
| [getSubtype()](#getSubtype--) | प्रभाव के उपप्रकार को निर्धारित करता है। |
| [setSubtype(int value)](#setSubtype-int-) | प्रभाव के उपप्रकार को निर्धारित करता है। |
| [getBehaviors()](#getBehaviors--) | प्रभाव के व्यवहार का संग्रह लौटाता है। |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | प्रभाव के व्यवहार का संग्रह लौटाता है। |
| [getTiming()](#getTiming--) | प्रभाव के समय मान को निर्धारित करता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | प्रभाव के समय मान को निर्धारित करता है। |
| [getTargetShape()](#getTargetShape--) | प्रभाव के लिए लक्ष्य आकार लौटाता है। |
| [getSound()](#getSound--) | प्रभाव के लिए एम्बेडेड साउंड निर्धारित करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | प्रभाव के लिए एम्बेडेड साउंड निर्धारित करता है। |
| [getStopPreviousSound()](#getStopPreviousSound--) | यह एट्रिब्यूट निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले साउंड को रोकता है या नहीं। |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | यह एट्रिब्यूट निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले साउंड को रोकता है या नहीं। |
| [getAfterAnimationType()](#getAfterAnimationType--) | प्रभाव के लिए एक बाद का एनीमेशन प्रकार निर्धारित करता है। |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | प्रभाव के लिए एक बाद का एनीमेशन प्रकार निर्धारित करता है। |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | प्रभाव के लिए एक बाद का एनीमेशन रंग निर्धारित करता है। |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | प्रभाव के लिए एक बाद का एनीमेशन रंग निर्धारित करता है। |
| [getAnimateTextType()](#getAnimateTextType--) | प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच विलंब निर्धारित करता है। |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच विलंब निर्धारित करता है। |
### getSequence() {#getSequence--}
``` 
public abstract ISequence getSequence()
```


इफ़ेक्ट के लिए एक क्रम लौटाता है। केवल पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence)।

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
``` 
public abstract ITextAnimation getTextAnimation()
```


टेक्स्ट एनीमेशन लौटाता है। केवल पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation)।

**Returns:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
``` 
public abstract int getPresetClassType()
```


प्रभाव की क्लास निर्धारित करता है। पढ़ने/लिखने योग्य [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)।

**Returns:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
``` 
public abstract void setPresetClassType(int value)
```


प्रभाव की क्लास निर्धारित करता है। पढ़ने/लिखने योग्य [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
``` 
public abstract int getType()
```


प्रभाव का प्रकार निर्धारित करता है। पढ़ने/लिखने योग्य [EffectType](../../com.aspose.slides/effecttype)।

**Returns:**
int
### setType(int value) {#setType-int-}
``` 
public abstract void setType(int value)
```


प्रभाव का प्रकार निर्धारित करता है। पढ़ने/लिखने योग्य [EffectType](../../com.aspose.slides/effecttype)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
``` 
public abstract int getSubtype()
```


प्रभाव के उपप्रकार को निर्धारित करता है। पढ़ने/लिखने योग्य [EffectSubtype](../../com.aspose.slides/effectsubtype)।

**Returns:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


प्रभाव के उपप्रकार को निर्धारित करता है। पढ़ने/लिखने योग्य [EffectSubtype](../../com.aspose.slides/effectsubtype)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


प्रभाव के व्यवहार का संग्रह लौटाता है। पढ़ने/लिखने योग्य [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)।

**Returns:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


प्रभाव के व्यवहार का संग्रह लौटाता है। पढ़ने/लिखने योग्य [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


प्रभाव के समय मान को निर्धारित करता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


प्रभाव के समय मान को निर्धारित करता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


प्रभाव के लिए लक्ष्य आकार लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


प्रभाव के लिए एम्बेडेड साउंड निर्धारित करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए इफ़ेक्ट्स क्रम प्राप्त करता है
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

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


प्रभाव के लिए एम्बेडेड साउंड निर्धारित करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // स्लाइड के लिए इफ़ेक्ट्स क्रम प्राप्त करता है
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


यह एट्रिब्यूट निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले साउंड को रोकता है या नहीं। पढ़ने/लिखने योग्य boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरे स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट Enhancements/Sound को "Stop Previous Sound" में बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


यह एट्रिब्यूट निर्दिष्ट करता है कि एनीमेशन प्रभाव पिछले साउंड को रोकता है या नहीं। पढ़ने/लिखने योग्य boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरे स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट Enhancements/Sound को "Stop Previous Sound" में बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


प्रभाव के लिए एक बाद का एनीमेशन प्रकार निर्धारित करता है। पढ़ने/लिखने योग्य AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation को "Hide on Next Mouse Click" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


प्रभाव के लिए एक बाद का एनीमेशन प्रकार निर्धारित करता है। पढ़ने/लिखने योग्य AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation को "Hide on Next Mouse Click" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


प्रभाव के लिए एक बाद का एनीमेशन रंग निर्धारित करता है। पढ़ने/लिखने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation प्रकार को "Color" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // इफ़ेक्ट की After animation रंग सेट करें।
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


प्रभाव के लिए एक बाद का एनीमेशन रंग निर्धारित करता है। पढ़ने/लिखने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation प्रकार को "Color" में बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // इफ़ेक्ट की After animation रंग सेट करें।
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। आकार के टेक्स्ट को अक्षर, शब्द या एक साथ एनीमेट किया जा सकता है। पढ़ने/लिखने योग्य AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की Animate text प्रकार को "By letter" में बदलें
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


प्रभाव के लिए एनीमेट टेक्स्ट प्रकार निर्धारित करता है। आकार के टेक्स्ट को अक्षर, शब्द या एक साथ एनीमेट किया जा सकता है। पढ़ने/लिखने योग्य AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की Animate text प्रकार को "By letter" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच विलंब निर्धारित करता है। सकारात्मक मान प्रभाव अवधि का प्रतिशत दर्शाता है। नकारात्मक मान सेकंड में विलंब दर्शाता है। पढ़ने/लिखने योग्य float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की Animate text प्रकार को "By word" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनीमेटेड टेक्स्ट भागों के बीच विलंब को प्रभाव अवधि के 20% पर सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returns:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच विलंब निर्धारित करता है। सकारात्मक मान प्रभाव अवधि का प्रतिशत दर्शाता है। नकारात्मक मान सेकंड में विलंब दर्शाता है। पढ़ने/लिखने योग्य float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की Animate text प्रकार को "By word" में बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनीमेटेड टेक्स्ट भागों के बीच विलंब को प्रभाव अवधि के 20% पर सेट करें।
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |