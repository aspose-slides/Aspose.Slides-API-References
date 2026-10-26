---
title: Effect
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एनिमेशन इफ़ेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/effect/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

एनिमेशन इफ़ेक्ट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSequence()](#getSequence--) | इफ़ेक्ट के लिए एक अनुक्रम लौटाता है। |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation केवल पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation)। |
| [getPresetClassType()](#getPresetClassType--) | इफ़ेक्ट की क्लास को परिभाषित करता है। |
| [setPresetClassType(int value)](#setPresetClassType-int-) | इफ़ेक्ट की क्लास को परिभाषित करता है। |
| [getType()](#getType--) | इफ़ेक्ट के प्रकार को परिभाषित करता है। |
| [setType(int value)](#setType-int-) | इफ़ेक्ट के प्रकार को परिभाषित करता है। |
| [getSubtype()](#getSubtype--) | इफ़ेक्ट के उपप्रकार को परिभाषित करता है। |
| [setSubtype(int value)](#setSubtype-int-) | इफ़ेक्ट के उपप्रकार को परिभाषित करता है। |
| [getBehaviors()](#getBehaviors--) | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। |
| [getTiming()](#getTiming--) | इफ़ेक्ट के टाइमिंग मान को परिभाषित करता है। |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | इफ़ेक्ट के टाइमिंग मान को परिभाषित करता है। |
| [getTargetShape()](#getTargetShape--) | इफ़ेक्ट के लिए लक्ष्य आकृति लौटाता है। |
| [getSound()](#getSound--) | इफ़ेक्ट के लिए एम्बेडेड साउंड परिभाषित करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | इफ़ेक्ट के लिए एम्बेडेड साउंड परिभाषित करता है। |
| [getStopPreviousSound()](#getStopPreviousSound--) | यह गुण निर्दिष्ट करता है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | यह गुण निर्दिष्ट करता है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। |
| [getAfterAnimationType()](#getAfterAnimationType--) | इफ़ेक्ट के लिए आफ्टर एनीमेशन प्रकार को परिभाषित करता है। |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | इफ़ेक्ट के लिए आफ्टर एनीमेशन प्रकार को परिभाषित करता है। |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | इफ़ेक्ट के लिए आफ्टर एनीमेशन रंग को परिभाषित करता है। |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | इफ़ेक्ट के लिए आफ्टर एनीमेशन रंग को परिभाषित करता है। |
| [getAnimateTextType()](#getAnimateTextType--) | इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

इफ़ेक्ट के लिए एक अनुक्रम लौटाता है। केवल पढ़ने योग्य [ISequence](../../com.aspose.slides/isequence)।

**वापसी:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation केवल पढ़ने योग्य [ITextAnimation](../../com.aspose.slides/itextanimation)।

**वापसी:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

इफ़ेक्ट की क्लास को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)।

**वापसी:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

इफ़ेक्ट की क्लास को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

इफ़ेक्ट के प्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectType](../../com.aspose.slides/effecttype)।

**वापसी:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

इफ़ेक्ट के प्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectType](../../com.aspose.slides/effecttype)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

इफ़ेक्ट के उपप्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectSubtype](../../com.aspose.slides/effectsubtype)।

**वापसी:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

इफ़ेक्ट के उपप्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [EffectSubtype](../../com.aspose.slides/effectsubtype)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। पढ़ने/लिखने योग्य [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)।

**वापसी:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

इफ़ेक्ट के लिए व्यवहार का संग्रह लौटाता है। पढ़ने/लिखने योग्य [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

इफ़ेक्ट के टाइमिंग मान को परिभाषित करता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**वापसी:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

इफ़ेक्ट के टाइमिंग मान को परिभाषित करता है। पढ़ने/लिखने योग्य [ITiming](../../com.aspose.slides/itiming)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

इफ़ेक्ट के लिए लक्ष्य आकृति लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

इफ़ेक्ट के लिए एम्बेडेड साउंड परिभाषित करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

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
>          // इफ़ेक्ट साउंड को बाइट एरे में निकालता है
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

इफ़ेक्ट के लिए एम्बेडेड साउंड परिभाषित करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

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
>          // इफ़ेक्ट साउंड को बाइट एरे में निकालता है
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

यह गुण निर्दिष्ट करता है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरे स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट की Enhancements/Sound को "Stop Previous Sound" पर बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

यह गुण निर्दिष्ट करता है कि एनीमेशन इफ़ेक्ट पिछले साउंड को रोकता है या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // दूसरे स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // दूसरे इफ़ेक्ट की Enhancements/Sound को "Stop Previous Sound" पर बदलें
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

इफ़ेक्ट के लिए आफ्टर एनीमेशन प्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव की After animation को "Hide on Next Mouse Click" पर बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

इफ़ेक्ट के लिए आफ्टर एनीमेशन प्रकार को परिभाषित करता है। पढ़ने/लिखने योग्य [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // प्रभाव की After animation को "Hide on Next Mouse Click" पर बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

इफ़ेक्ट के लिए आफ्टर एनीमेशन रंग को परिभाषित करता है। पढ़ने/लिखने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation प्रकार को "Color" पर बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // इफ़ेक्ट की After animation रंग सेट करें.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

इफ़ेक्ट के लिए आफ्टर एनीमेशन रंग को परिभाषित करता है। पढ़ने/लिखने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट की After animation प्रकार को "Color" पर बदलें
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // इफ़ेक्ट की After animation रंग सेट करें.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। The shape text can be animated by letter, by word or all at once. पढ़ने/लिखने योग्य AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By letter" पर बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

इफ़ेक्ट के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। The shape text can be animated by letter, by word or all at once. पढ़ने/लिखने योग्य AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int))।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By letter" पर बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान इफ़ेक्ट की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By word" पर बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनिमेटेड टेक्स्ट भागों के बीच देरी को प्रभाव की अवधि के 20% पर सेट करें.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान इफ़ेक्ट की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // इफ़ेक्ट के Animate text प्रकार को "By word" पर बदलें
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // एनिमेटेड टेक्स्ट भागों के बीच देरी को प्रभाव की अवधि के 20% पर सेट करें.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject