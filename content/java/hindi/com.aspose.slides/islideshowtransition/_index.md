---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
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
| [getSound()](#getSound--) | एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [getSoundMode()](#getSoundMode--) | स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या लौटाता है। |
| [setSoundMode(int value)](#setSoundMode-int-) | स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या लौटाता है। |
| [getSoundLoop()](#getSoundLoop--) | यह विशेषता निर्धारित करती है कि क्या साउंड अगली साउंड इवेंट होने तक स्लाइडशो में लूप करेगा। |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | यह विशेषता निर्धारित करती है कि क्या साउंड अगली साउंड इवेंट होने तक स्लाइडशो में लूप करेगा। |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [getAdvanceAfter()](#getAdvanceAfter--) | यह विशेषता निर्धारित करती है कि क्या स्लाइडशो एक निश्चित समय के बाद अगली स्लाइड पर जाएगा। |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | यह विशेषता निर्धारित करती है कि क्या स्लाइडशो एक निश्चित समय के बाद अगली स्लाइड पर जाएगा। |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | मिलिसेकंड में समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | मिलिसेकंड में समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [getSpeed()](#getSpeed--) | वर्तमान स्लाइड से अगली स्लाइड में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। |
| [setSpeed(int value)](#setSpeed-int-) | वर्तमान स्लाइड से अगली स्लाइड में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। |
| [getValue()](#getValue--) | स्लाइड शो ट्रांज़िशन मान। |
| [getType()](#getType--) | ट्रांज़िशन का प्रकार। |
| [setType(int value)](#setType-int-) | ट्रांज़िशन का प्रकार। |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | निर्दिष्ट करता है कि यह ध्वनि अंतर्निहित ध्वनि है या नहीं। |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | निर्दिष्ट करता है कि यह ध्वनि अंतर्निहित ध्वनि है या नहीं। |
| [getSoundName()](#getSoundName--) | ट्रांज़िशन की ध्वनि के लिए एक मानव-पठनीय नाम निर्दिष्ट करता है। |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ट्रांज़िशन की ध्वनि के लिए एक मानव-पठनीय नाम निर्दिष्ट करता है। |
| [getDuration()](#getDuration--) | स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता है या सेट करता है। |
| [setDuration(int value)](#setDuration-int-) | स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता है या सेट करता है। |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ें-लिखें [IAudio](../../com.aspose.slides/iaudio).

**वापसी:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ें-लिखें [IAudio](../../com.aspose.slides/iaudio).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या लौटाता है। पढ़ें-लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**वापसी:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड को सेट या लौटाता है। पढ़ें-लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

यह विशेषता निर्धारित करती है कि क्या ध्वनि अगले ध्वनि इवेंट तक स्लाइडशो में लूप करेगी। पढ़ें-लिखें बूलियन।

**वापसी:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

यह विशेषता निर्धारित करती है कि क्या ध्वनि अगले ध्वनि इवेंट तक स्लाइडशो में लूप करेगी। पढ़ें-लिखें बूलियन।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह विशेषता निर्दिष्ट नहीं की गई है तो true मान मान लिया जाता है। पढ़ें-लिखें बूलियन।

**वापसी:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह विशेषता निर्दिष्ट नहीं की गई है तो true मान मान लिया जाता है। पढ़ें-लिखें बूलियन।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

यह विशेषता निर्धारित करती है कि क्या स्लाइडशो एक निश्चित समय के बाद अगली स्लाइड पर जाएगा। पढ़ें/लिखें बूलियन।

--------------------

> ``` 
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग चुना गया है या नहीं
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time मान प्राप्त करें
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**वापसी:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

यह विशेषता निर्धारित करती है कि क्या स्लाइडशो एक निश्चित समय के बाद अगली स्लाइड पर जाएगा। पढ़ें/लिखें बूलियन।

--------------------

> ``` 
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहली स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जाँचें कि Advance Slide After फ़्लैग चुना गया है या नहीं
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time मान प्राप्त करें
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

ट्रांज़िशन शुरू होने के बाद मिलिसेकंड में समय निर्दिष्ट करता है। यह सेटिंग advClick विशेषता के साथ उपयोग की जा सकती है। यदि यह विशेषता निर्दिष्ट नहीं की गई है तो माना जाता है कि कोई स्वतः-एडवांस नहीं होगा। पढ़ें-लिखें लॉन्ग।

**वापसी:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

ट्रांज़िशन शुरू होने के बाद मिलिसेकंड में समय निर्दिष्ट करता है। यह सेटिंग advClick विशेषता के साथ उपयोग की जा सकती है। यदि यह विशेषता निर्दिष्ट नहीं की गई है तो माना जाता है कि कोई स्वतः-एडवांस नहीं होगा। पढ़ें-लिखें लॉन्ग।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

वर्तमान स्लाइड से अगली स्लाइड में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। पढ़ें-लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**वापसी:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

वर्तमान स्लाइड से अगली स्लाइड में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। पढ़ें-लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

स्लाइड शो ट्रांज़िशन मान। केवल-पढ़ने योग्य [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)।

**वापसी:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

ट्रांज़िशन का प्रकार। पढ़ें-लिखें [TransitionType](../../com.aspose.slides/transitiontype)।

**वापसी:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

ट्रांज़िशन का प्रकार। पढ़ें-लिखें [TransitionType](../../com.aspose.slides/transitiontype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

निर्दिष्ट करता है कि यह ध्वनि अंतर्निहित ध्वनि है या नहीं। यदि यह विशेषता true पर सेट की गई है तो उत्पन्न करने वाला अनुप्रयोग इस ध्वनि के लिए सूची में निर्दिष्ट नाम विशेषता को जांचने के लिए सतर्क किया जाता है और फिर आवश्यकतानुसार एक कस्टम नाम या UI प्रदर्शित कर सकता है। पढ़ें-लिखें बूलियन।

**वापसी:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

निर्दिष्ट करता है कि यह ध्वनि अंतर्निहित ध्वनि है या नहीं। यदि यह विशेषता true पर सेट की गई है तो उत्पन्न करने वाला अनुप्रयोग इस ध्वनि के लिए सूची में निर्दिष्ट नाम विशेषता को जांचने के लिए सतर्क किया जाता है और फिर आवश्यकतानुसार एक कस्टम नाम या UI प्रदर्शित कर सकता है। पढ़ें-लिखें बूलियन।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

ट्रांज़िशन की ध्वनि के लिए एक मानव-पठनीय नाम निर्दिष्ट करता है। (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) गुण को ध्वनि नाम प्राप्त या सेट करने के लिए असाइन करना आवश्यक है। पढ़ें-लिखें String।

**वापसी:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

ट्रांज़िशन की ध्वनि के लिए एक मानव-पठनीय नाम निर्दिष्ट करता है। \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) गुण को ध्वनि नाम प्राप्त या सेट करने के लिए असाइन करना आवश्यक है। पढ़ें-लिखें String।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता है या सेट करता है। पढ़ें/लिखें int।

--------------------

PresentationML स्कीमा में p:transition तत्व के p14:dur विशेषता के समतुल्य है। यदि सेट नहीं किया गया है, तो अवधि स्वतः \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) गुण और ट्रांज़िशन प्रकार के आधार पर निर्धारित की जाती है।

**वापसी:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता है या सेट करता है। पढ़ें/लिखें int।

--------------------

PresentationML स्कीमा में p:transition तत्व के p14:dur विशेषता के समतुल्य है। यदि सेट नहीं किया गया है, तो अवधि स्वतः \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) गुण और ट्रांज़िशन प्रकार के आधार पर निर्धारित की जाती है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |