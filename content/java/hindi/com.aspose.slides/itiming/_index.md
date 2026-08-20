---
title: ITiming
second_title: Aspose.Slides for Java API Reference
description: Represents animation timing.
type: docs
url: /hi/com.aspose.slides/itiming/
---```
public interface ITiming
```

एनिमेशन टाइमिंग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | त्वरण व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। |
| [setAccelerate(float value)](#setAccelerate-float-) | त्वरण व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। |
| [getDecelerate()](#getDecelerate--) | मंदन व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। |
| [setDecelerate(float value)](#setDecelerate-float-) | मंदन व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। |
| [getAutoReverse()](#getAutoReverse--) | फ़ॉरवर्ड दिशा में चलने के बाद एनिमेशन को स्वचालित रूप से रीवर्‍स में चलाने के बारे में वर्णन करता है। |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | फ़ॉरवर्ड दिशा में चलने के बाद एनिमेशन को स्वचालित रूप से रीवर्‍स में चलाने के बारे में वर्णन करता है। |
| [getDuration()](#getDuration--) | एनिमेशन प्रभाव की अवधि को वर्णित करता है। |
| [setDuration(float value)](#setDuration-float-) | एनिमेशन प्रभाव की अवधि को वर्णित करता है। |
| [getRepeatCount()](#getRepeatCount--) | प्रभाव को दोहराने की संख्या को वर्णित करता है। |
| [setRepeatCount(float value)](#setRepeatCount-float-) | प्रभाव को दोहराने की संख्या को वर्णित करता है। |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | यह विशेषता निर्धारित करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | यह विशेषता निर्धारित करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | यह विशेषता निर्धारित करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | यह विशेषता निर्धारित करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। |
| [getRepeatDuration()](#getRepeatDuration--) | प्रभाव को दोहराने की संख्या को वर्णित करता है। |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | प्रभाव को दोहराने की संख्या को वर्णित करता है। |
| [getRestart()](#getRestart--) | निर्धारित करता है कि प्रभाव पूर्ण होने के बाद पुनरारंभ होगा या नहीं। |
| [setRestart(int value)](#setRestart-int-) | निर्धारित करता है कि प्रभाव पूर्ण होने के बाद पुनरारंभ होगा या नहीं। |
| [getSpeed()](#getSpeed--) | टाइमिंग को तेज (या धीमा) करने के लिए प्रतिशत को निर्दिष्ट करता है। |
| [setSpeed(float value)](#setSpeed-float-) | टाइमिंग को तेज (या धीमा) करने के लिए प्रतिशत को निर्दिष्ट करता है। |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | ट्रिगर के बाद देरी समय को वर्णित करता है। |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | ट्रिगर के बाद देरी समय को वर्णित करता है। |
| [getTriggerType()](#getTriggerType--) | ट्रिगर प्रकार को वर्णित करता है। |
| [setTriggerType(int value)](#setTriggerType-int-) | ट्रिगर प्रकार को वर्णित करता है। |
| [getRewind()](#getRewind--) | यह विशेषता निर्धारित करती है कि प्रभाव चलने के बाद रीवाइंड होगा या नहीं। |
| [setRewind(boolean value)](#setRewind-boolean-) | यह विशेषता निर्धारित करती है कि प्रभाव चलने के बाद रीवाइंड होगा या नहीं। |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

त्वरण व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

त्वरण व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

मंदन व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

मंदन व्यवहार प्रभाव की अवधि का प्रतिशत वर्णन करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

फ़ॉरवर्ड दिशा में चलने के बाद एनिमेशन को स्वचालित रूप से रीवर्‍स में चलाने के बारे में वर्णन करता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

फ़ॉरवर्ड दिशा में चलने के बाद एनिमेशन को स्वचालित रूप से रीवर्‍स में चलाने के बारे में वर्णन करता है। पढ़ें/लिखें boolean.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

एनिमेशन प्रभाव की अवधि को वर्णित करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

एनिमेशन प्रभाव की अवधि को वर्णित करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

प्रभाव को दोहराने की संख्या को वर्णित करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

प्रभाव को दोहराने की संख्या को वर्णित करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

यह विशेषता निर्धारित करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "स्लाइड के अंत तक" बदलें
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

यह विशेषता निर्धारित करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "स्लाइड के अंत तक" बदलें
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

यह विशेषता निर्धारित करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "अगली क्लिक तक" बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

यह विशेषता निर्धारित करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रिपीट को "अगली क्लिक तक" बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

प्रभाव को दोहराने की संख्या को वर्णित करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

प्रभाव को दोहराने की संख्या को वर्णित करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

निर्धारित करता है कि प्रभाव पूर्ण होने के बाद पुनरारंभ होगा या नहीं। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**वापसी:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

निर्धारित करता है कि प्रभाव पूर्ण होने के बाद पुनरारंभ होगा या नहीं। पढ़ें/लिखें [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

टाइमिंग को तेज (या धीमा) करने के लिए प्रतिशत को निर्दिष्ट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

टाइमिंग को तेज (या धीमा) करने के लिए प्रतिशत को निर्दिष्ट करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

ट्रिगर के बाद देरी समय को वर्णित करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

ट्रिगर के बाद देरी समय को वर्णित करता है। पढ़ें/लिखें float.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

ट्रिगर प्रकार को वर्णित करता है। पढ़ें/लिखें [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**वापसी:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

ट्रिगर प्रकार को वर्णित करता है। पढ़ें/लिखें [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

यह विशेषता निर्धारित करती है कि प्रभाव चलने के बाद रीवाइंड होगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रीवाइंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

यह विशेषता निर्धारित करती है कि प्रभाव चलने के बाद रीवाइंड होगा या नहीं। पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // इफ़ेक्ट की टाइमिंग/रीवाइंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |