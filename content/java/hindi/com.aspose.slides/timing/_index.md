---
title: Timing
second_title: Aspose.Slides के लिए जावा API रेफ़रेंस
description: एनिमेशन टाइमिंग का प्रतिनिधित्व करता है।
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

एनिमेशन टाइमिंग का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | त्वरित व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। |
| [setAccelerate(float value)](#setAccelerate-float-) | त्वरित व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। |
| [getDecelerate()](#getDecelerate--) | धीमी गति वाले व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। |
| [setDecelerate(float value)](#setDecelerate-float-) | धीमी गति वाले व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। |
| [getAutoReverse()](#getAutoReverse--) | वर्णन करता है कि क्या आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टे दिशा में चलाया जाए। |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | वर्णन करता है कि क्या आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टे दिशा में चलाया जाए। |
| [getDuration()](#getDuration--) | एनिमेशन प्रभाव की अवधि का वर्णन करता है। |
| [setDuration(float value)](#setDuration-float-) | एनिमेशन प्रभाव की अवधि का वर्णन करता है। |
| [getRepeatCount()](#getRepeatCount--) | प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। |
| [setRepeatCount(float value)](#setRepeatCount-float-) | प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | यह विशेषता निर्दिष्ट करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। |
| [getRepeatDuration()](#getRepeatDuration--) | प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। |
| [getRestart()](#getRestart--) | निर्दिष्ट करता है कि क्या प्रभाव पूर्ण होने के बाद पुनः शुरू होगा। |
| [setRestart(int value)](#setRestart-int-) | निर्दिष्ट करता है कि क्या प्रभाव पूर्ण होने के बाद पुनः शुरू होगा। |
| [getRewind()](#getRewind--) | यह विशेषता निर्दिष्ट करती है कि प्ले समाप्त होने पर प्रभाव को पीछे ले जाया जाएगा या नहीं। |
| [setRewind(boolean value)](#setRewind-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्ले समाप्त होने पर प्रभाव को पीछे ले जाया जाएगा या नहीं। |
| [getSpeed()](#getSpeed--) | समय को तेज (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। |
| [setSpeed(float value)](#setSpeed-float-) | समय को तेज (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | ट्रिगर के बाद विलंब समय का वर्णन करता है। |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | ट्रिगर के बाद विलंब समय का वर्णन करता है। |
| [getTriggerType()](#getTriggerType--) | ट्रिगर प्रकार का वर्णन करता है। |
| [setTriggerType(int value)](#setTriggerType-int-) | ट्रिगर प्रकार का वर्णन करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

त्वरित व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

त्वरित व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

धीमी गति वाले व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

धीमी गति वाले व्यवहार प्रभाव की अवधि प्रतिशत का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

वर्णन करता है कि क्या आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टे दिशा में चलाया जाए। पढ़ें/लिखें boolean.

**रिटर्न मान:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

वर्णन करता है कि क्या आगे की दिशा में चलाने के बाद एनीमेशन को स्वचालित रूप से उल्टे दिशा में चलाया जाए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

एनिमेशन प्रभाव की अवधि का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

एनिमेशन प्रभाव की अवधि का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "Until End of Slide" में बदलें
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न मान:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "Until End of Slide" में बदलें
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

यह विशेषता निर्दिष्ट करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "Until Next Click" में बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न मान:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "Until Next Click" में बदलें
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

प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

प्रभाव के दोहराए जाने की संख्या का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

निर्दिष्ट करता है कि क्या प्रभाव पूर्ण होने के बाद पुनः शुरू होगा। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**रिटर्न मान:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

निर्दिष्ट करता है कि क्या प्रभाव पूर्ण होने के बाद पुनः शुरू होगा। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

यह विशेषता निर्दिष्ट करती है कि प्ले समाप्त होने पर प्रभाव को पीछे ले जाया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रीवाइंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न मान:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्ले समाप्त होने पर प्रभाव को पीछे ले जाया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रीवाइंड चालू करें।
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

समय को तेज (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

समय को तेज (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

ट्रिगर के बाद विलंब समय का वर्णन करता है। पढ़ें/लिखें float.

**रिटर्न मान:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

ट्रिगर के बाद विलंब समय का वर्णन करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

ट्रिगर प्रकार का वर्णन करता है। पढ़ें/लिखें [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**रिटर्न मान:**
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

Parent_Immediate वस्तु लौटाता है। केवल पढ़ने योग्य IDOMObject.

**रिटर्न मान:**
com.aspose.slides.IDOMObject