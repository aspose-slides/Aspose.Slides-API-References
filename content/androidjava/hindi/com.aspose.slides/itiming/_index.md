---
title: ITiming
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एनीमेशन टाइमिंग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itiming/
---```
public interface ITiming
```

एनीमेशन टाइमिंग का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | अवधि में तेज़ी व्यवहार प्रभाव के प्रतिशत को वर्णन करता है। |
| [setAccelerate(float value)](#setAccelerate-float-) | अवधि में तेज़ी व्यवहार प्रभाव के प्रतिशत को वर्णन करता है। |
| [getDecelerate()](#getDecelerate--) | अवधि में मंदी व्यवहार प्रभाव के प्रतिशत को वर्णन करता है। |
| [setDecelerate(float value)](#setDecelerate-float-) | अवधि में मंदी व्यवहार प्रभाव के प्रतिशत को वर्णन करता है। |
| [getAutoReverse()](#getAutoReverse--) | अग्र दिशा में चलने के बाद एनीमेशन को स्वचालित रूप से обрат क्रम में चलाने का वर्णन करता है। |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | अग्र दिशा में चलने के बाद एनीमेशन को स्वचालित रूप से обрат क्रम में चलाने का वर्णन करता है। |
| [getDuration()](#getDuration--) | एनीमेशन प्रभाव की अवधि का वर्णन करता है। |
| [setDuration(float value)](#setDuration-float-) | एनीमेशन प्रभाव की अवधि का वर्णन करता है। |
| [getRepeatCount()](#getRepeatCount--) | प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। |
| [setRepeatCount(float value)](#setRepeatCount-float-) | प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | यह विशेषता निर्दिष्ट करती है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। |
| [getRepeatDuration()](#getRepeatDuration--) | प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। |
| [getRestart()](#getRestart--) | यह निर्दिष्ट करता है कि प्रभाव पूर्ण होने के बाद पुनः प्रारंभ होगा या नहीं। |
| [setRestart(int value)](#setRestart-int-) | यह निर्दिष्ट करता है कि प्रभाव पूर्ण होने के बाद पुनः प्रारंभ होगा या नहीं। |
| [getSpeed()](#getSpeed--) | टाइमिंग को तेज़ (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। |
| [setSpeed(float value)](#setSpeed-float-) | टाइमिंग को तेज़ (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | ट्रिगर के बाद देरी समय का वर्णन करता है। |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | ट्रिगर के बाद देरी समय का वर्णन करता है। |
| [getTriggerType()](#getTriggerType--) | ट्रिगर प्रकार का वर्णन करता है। |
| [setTriggerType(int value)](#setTriggerType-int-) | ट्रिगर प्रकार का वर्णन करता है। |
| [getRewind()](#getRewind--) | यह विशेषता निर्दिष्ट करती है कि प्रभाव खेलने के बाद रीविंड होगा या नहीं। |
| [setRewind(boolean value)](#setRewind-boolean-) | यह विशेषता निर्दिष्ट करती है कि प्रभाव खेलने के बाद रीविंड होगा या नहीं। |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

तीव्रता व्यवहार प्रभाव की अवधि प्रतिशत को वर्णन करता है। पढ़ने/लिखने योग्य float.

**रिटर्न:**  
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

तीव्रता व्यवहार प्रभाव की अवधि प्रतिशत को वर्णन करता है। पढ़ने/लिखने योग्य float.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

मंदी व्यवहार प्रभाव की अवधि प्रतिशत को वर्णन करता है। पढ़ने/लिखने योग्य float.

**रिटर्न:**  
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

मंदी व्यवहार प्रभाव की अवधि प्रतिशत को वर्णन करता है। पढ़ने/लिखने योग्य float.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

अग्र दिशा में चलने के बाद एनीमेशन को स्वचालित रूप से обрат क्रम में चलाने का वर्णन करता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

अग्र दिशा में चलने के बाद एनीमेशन को स्वचालित रूप से обрат क्रम में चलाने का वर्णन करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

एनीमेशन प्रभाव की अवधि का वर्णन करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

एनीमेशन प्रभाव की अवधि का वर्णन करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/दोहराव "स्लाइड के अंत तक" में बदलें
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**  
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/दोहराव "स्लाइड के अंत तक" में बदलें
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
public abstract boolean getRepeatUntilNextClick()
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/दोहराव "अगले क्लिक तक" में बदलें
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**  
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव अगले क्लिक तक दोहराया जाएगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/दोहराव "अगले क्लिक तक" में बदलें
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
public abstract float getRepeatDuration()
```

प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

प्रभाव को कितनी बार दोहराना चाहिए, इसका वर्णन करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

यह निर्दिष्ट करता है कि प्रभाव पूर्ण होने के बाद पुनः प्रारंभ होगा या नहीं। पढ़ने/लिखने योग्य [EffectRestartType](../../com.aspose.slides/effectrestarttype)।

**रिटर्न:**  
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

यह निर्दिष्ट करता है कि प्रभाव पूर्ण होने के बाद पुनः प्रारंभ होगा या नहीं। पढ़ने/लिखने योग्य [EffectRestartType](../../com.aspose.slides/effectrestarttype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

टाइमिंग को तेज़ (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

टाइमिंग को तेज़ (या धीमा) करने के प्रतिशत को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

ट्रिगर के बाद देरी समय का वर्णन करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

ट्रिगर के बाद देरी समय का वर्णन करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

ट्रिगर प्रकार का वर्णन करता है। पढ़ने/लिखने योग्य [EffectTriggerType](../../com.aspose.slides/effecttriggertype)।

**रिटर्न:**  
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

ट्रिगर प्रकार का वर्णन करता है। पढ़ने/लिखने योग्य [EffectTriggerType](../../com.aspose.slides/effecttriggertype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव खेलने के बाद रीविंड होगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/रीविंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**  
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

यह विशेषता निर्दिष्ट करती है कि प्रभाव खेलने के बाद रीविंड होगा या नहीं। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करें
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // मुख्य अनुक्रम का पहला इफ़ेक्ट प्राप्त करें।
>      IEffect effect = effectsSequence.get_Item(0);
>      // प्रभाव का टाइमिंग/रीविंड चालू करें।
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |