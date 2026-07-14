---
title: Timing
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एनीमेशन टाइमिंग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/timing/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

एनीमेशन टाइमिंग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | विवरण देता है अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत। |
| [setAccelerate(float value)](#setAccelerate-float-) | विवरण देता है अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत। |
| [getDecelerate()](#getDecelerate--) | विवरण देता है अवधि के मंदी व्यवहार प्रभाव का प्रतिशत। |
| [setDecelerate(float value)](#setDecelerate-float-) | विवरण देता है अवधि के मंदी व्यवहार प्रभाव का प्रतिशत। |
| [getAutoReverse()](#getAutoReverse--) | विवरण देता है कि आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टा चलाया जाए या नहीं। |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | विवरण देता है कि आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टा चलाया जाए या नहीं। |
| [getDuration()](#getDuration--) | विवरण देता है एनीमेशन प्रभाव की अवधि। |
| [setDuration(float value)](#setDuration-float-) | विवरण देता है एनीमेशन प्रभाव की अवधि। |
| [getRepeatCount()](#getRepeatCount--) | विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। |
| [setRepeatCount(float value)](#setRepeatCount-float-) | विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | यह गुण निर्दिष्ट करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | यह गुण निर्दिष्ट करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। |
| [getRepeatDuration()](#getRepeatDuration--) | विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | विवरण देता हैं कि प्रभाव को कितनी बार दोहराया जाना चाहिए। |
| [getRestart()](#getRestart--) | निर्देशित करता है कि प्रभाव पूर्ण होने के बाद पुनः शुरू किया जाए या नहीं। |
| [setRestart(int value)](#setRestart-int-) | निर्देशित करता है कि प्रभाव पूर्ण होने के बाद पुनः शुरू किया जाए या नहीं। |
| [getRewind()](#getRewind--) | यह गुण निर्दिष्ट करता है कि प्रभाव खेल समाप्त होने पर फिर से शुरू होगा या नहीं। |
| [setRewind(boolean value)](#setRewind-boolean-) | यह गुण निर्दिष्ट करता है कि प्रभाव खेल समाप्त होने पर फिर से शुरू होगा या नहीं। |
| [getSpeed()](#getSpeed--) | समय को तेज (या धीमा) करने के लिए प्रतिशत निर्दिष्ट करता है। |
| [setSpeed(float value)](#setSpeed-float-) | समय को तेज (या धीमा) करने के लिए प्रतिशत निर्दिष्ट करता है। |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | ट्रिगर के बाद की देरी समय का वर्णन करता है। |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | ट्रिगर के बाद की देरी समय का वर्णन करता है। |
| [getTriggerType()](#getTriggerType--) | ट्रिगर प्रकार का वर्णन करता है। |
| [setTriggerType(int value)](#setTriggerType-int-) | ट्रिगर प्रकार का वर्णन करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

विवरण देता है अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत। पढ़ें/लिखें float.

**रिटर्न:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

विवरण देता है अवधि के त्वरित व्यवहार प्रभाव का प्रतिशत। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

विवरण देता है अवधि के मंदी व्यवहार प्रभाव का प्रतिशत। पढ़ें/लिखें float.

**रिटर्न:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

विवरण देता है अवधि के मंदी व्यवहार प्रभाव का प्रतिशत। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

विवरण देता है कि आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टा चलाया जाए या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

विवरण देता है कि आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टा चलाया जाए या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

विवरण देता है एनीमेशन प्रभाव की अवधि। पढ़ें/लिखें float.

**रिटर्न:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

विवरण देता है एनीमेशन प्रभाव की अवधि। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। पढ़ें/लिखें float.

**रिटर्न:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट के टाइमिंग/दोहराव को "स्लाइड के अंत तक" बदलें
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

यह गुण निर्दिष्ट करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट के टाइमिंग/दोहराव को "अगले क्लिक तक" बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

यह गुण निर्दिष्ट करता है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट के टाइमिंग/दोहराव को "अगले क्लिक तक" बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। पढ़ें/लिखें float.

**रिटर्न:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

विवरण देता है कि प्रभाव को कितनी बार दोहराया जाना चाहिए। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

निर्देशित करता है कि प्रभाव पूर्ण होने के बाद पुनः शुरू किया जाए या नहीं। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**रिटर्न:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

निर्देशित करता है कि प्रभाव पूर्ण होने के बाद पुनः शुरू किया जाए या नहीं। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

यह गुण निर्दिष्ट करता है कि प्रभाव खेल समाप्त होने पर फिर से शुरू होगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट का टाइमिंग/रीवाइंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

यह गुण निर्दिष्ट करता है कि प्रभाव खेल समाप्त होने पर फिर से शुरू होगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट का टाइमिंग/रीवाइंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

समय को तेज (या धीमा) करने के लिए प्रतिशत निर्दिष्ट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

समय को तेज (या धीमा) करने के लिए प्रतिशत निर्दिष्ट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

ट्रिगर के बाद की देरी समय का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

ट्रिगर के बाद की देरी समय का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

ट्रिगर प्रकार का वर्णन करता है। पढ़ें/लिखें [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**रिटर्न:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

ट्रिगर प्रकार का वर्णन करता है। पढ़ें/लिखें [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject