---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /hi/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

स्लाइड शो ट्रांज़िशन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSound()](#getSound--) | एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [getSoundMode()](#getSoundMode--) | स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या प्राप्त करता है। |
| [setSoundMode(int value)](#setSoundMode-int-) | स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या प्राप्त करता है। |
| [getSoundLoop()](#getSoundLoop--) | यह गुण निर्दिष्ट करता है कि ध्वनि अगले साउंड इवेंट होने तक लूप होगी। |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | यह गुण निर्दिष्ट करता है कि ध्वनि अगले साउंड इवेंट होने तक लूप होगी। |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [getAdvanceAfter()](#getAdvanceAfter--) | यह गुण निर्दिष्ट करता है कि स्लाइडशो निर्धारित समय के बाद अगली स्लाइड पर जाएगा। |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | यह गुण निर्दिष्ट करता है कि स्लाइडशो निर्धारित समय के बाद अगली स्लाइड पर जाएगा। |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | वह समय (मिलीसेकंड में) निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | वह समय (मिलीसेकंड में) निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [getSpeed()](#getSpeed--) | वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के समय उपयोग की जाने वाली गति को निर्दिष्ट करता है। |
| [setSpeed(int value)](#setSpeed-int-) | वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के समय उपयोग की जाने वाली गति को निर्दिष्ट करता है। |
| [getValue()](#getValue--) | स्लाइड शो ट्रांज़िशन मान। |
| [getType()](#getType--) | ट्रांज़िशन का प्रकार। |
| [setType(int value)](#setType-int-) | ट्रांज़िशन का प्रकार। |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | यह निर्दिष्ट करता है कि यह साउंड अंतर्निर्मित साउंड है या नहीं। |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | यह निर्दिष्ट करता है कि यह साउंड अंतर्निर्मित साउंड है या नहीं। |
| [getSoundName()](#getSoundName--) | ट्रांज़िशन साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ट्रांज़िशन साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। |
| [getDuration()](#getDuration--) | स्लाइड ट्रांज़िशन प्रभाव की अवधि (मिलीसेकंड में) को प्राप्त करता है या सेट करता है। |
| [setDuration(int value)](#setDuration-int-) | स्लाइड ट्रांज़िशन प्रभाव की अवधि (मिलीसेकंड में) को प्राप्त करता है या सेट करता है। |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [IAudio](../../com.aspose.slides/iaudio).

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [IAudio](../../com.aspose.slides/iaudio).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```


स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या प्राप्त करता है। पढ़ने-लिखने योग्य [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**रिटर्न:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```


स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या प्राप्त करता है। पढ़ने-लिखने योग्य [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


यह गुण निर्दिष्ट करता है कि ध्वनि अगले साउंड इवेंट होने तक लूप होगी। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


यह गुण निर्दिष्ट करता है कि ध्वनि अगले साउंड इवेंट होने तक लूप होगी। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


निर्देशित करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह गुण निर्दिष्ट नहीं किया गया तो true मान माना जाता है। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


निर्देशित करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह गुण निर्दिष्ट नहीं किया गया तो true मान माना जाता है। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


यह गुण निर्दिष्ट करता है कि स्लाइडशो निर्धारित समय के बाद अगली स्लाइड पर जाएगा। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहला स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग चेक किया गया है या नहीं
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time मान प्राप्त करें
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```


यह गुण निर्दिष्ट करता है कि स्लाइडशो निर्धारित समय के बाद अगली स्लाइड पर जाएगा। पढ़ने/लिखने योग्य boolean।

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहला स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जाँचें कि Advance Slide After फ़्लैग चेक किया गया है या नहीं
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time मान प्राप्त करें
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```


ट्रांज़िशन शुरू होने के बाद का समय (मिलीसेकंड में) निर्दिष्ट करता है। यह सेटिंग advClick गुण के साथ उपयोग की जा सकती है। यदि यह गुण निर्दिष्ट नहीं किया गया तो कोई ऑटो-एडवांस नहीं होगा। पढ़ने-लिखने योग्य long।

**रिटर्न:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```


ट्रांज़िशन शुरू होने के बाद का समय (मिलीसेकंड में) निर्दिष्ट करता है। यह सेटिंग advClick गुण के साथ उपयोग की जा सकती है। यदि यह गुण निर्दिष्ट नहीं किया गया तो कोई ऑटो-एडवांस नहीं होगा। पढ़ने-लिखने योग्य long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```


वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के समय उपयोग की जाने वाली गति को निर्दिष्ट करता है। पढ़ने-लिखने योग्य [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**रिटर्न:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```


वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के समय उपयोग की जाने वाली गति को निर्दिष्ट करता है। पढ़ने-लिखने योग्य [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```


स्लाइड शो ट्रांज़िशन मान। केवल-पढ़ने योग्य [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)।

**रिटर्न:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```


ट्रांज़िशन का प्रकार। पढ़ने-लिखने योग्य [TransitionType](../../com.aspose.slides/transitiontype)।

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


ट्रांज़िशन का प्रकार। पढ़ने-लिखने योग्य [TransitionType](../../com.aspose.slides/transitiontype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```


यह निर्दिष्ट करता है कि यह साउंड अंतर्निर्मित साउंड है या नहीं। यदि यह गुण true पर सेट किया गया तो जनरेटिंग एप्लिकेशन को इस साउंड के लिए नाम गुण की जांच करनी चाहिए और आवश्यकतानुसार कस्टम नाम या UI प्रदर्शित करना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```


यह निर्दिष्ट करता है कि यह साउंड अंतर्निर्मित साउंड है या नहीं। यदि यह गुण true पर सेट किया गया तो जनरेटिंग एप्लिकेशन को इस साउंड के लिए नाम गुण की जांच करनी चाहिए और आवश्यकतानुसार कस्टम नाम या UI प्रदर्शित करना चाहिए। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```


ट्रांज़िशन साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) प्रॉपर्टी को साउंड नाम प्राप्त या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ने-लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```


ट्रांज़िशन साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) प्रॉपर्टी को साउंड नाम प्राप्त या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ने-लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```


स्लाइड ट्रांज़िशन प्रभाव की अवधि (मिलीसेकंड में) को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int।

--------------------

p14:dur गुण के साथ p:transition तत्व के PresentationML स्कीमा में मेल खाता है। यदि सेट नहीं किया गया तो अवधि स्वतः \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) प्रॉपर्टी और ट्रांज़िशन प्रकार के आधार पर निर्धारित होती है।

**रिटर्न:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```


स्लाइड ट्रांज़िशन प्रभाव की अवधि (मिलीसेकंड में) को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int।

--------------------

p14:dur गुण के साथ p:transition तत्व के PresentationML स्कीमा में मेल खाता है। यदि सेट नहीं किया गया तो अवधि स्वतः \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) प्रॉपर्टी और ट्रांज़िशन प्रकार के आधार पर निर्धारित होती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |