---
title: SlideShowTransition
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइड शो ट्रांज़िशन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/slideshowtransition/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

स्लाइड शो ट्रांज़िशन का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSound()](#getSound--) | एंबेडेड ऑडियो डेटा को लौटाता या सेट करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | एंबेडेड ऑडियो डेटा को लौटाता या सेट करता है। |
| [getSoundMode()](#getSoundMode--) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता या लौटाता है। |
| [setSoundMode(int value)](#setSoundMode-int-) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता या लौटाता है। |
| [getSoundLoop()](#getSoundLoop--) | यह गुण निर्दिष्ट करता है कि क्या ध्वनि स्लाइडशो में अगले ध्वनि इवेंट तक लूप करेगी। |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | यह गुण निर्दिष्ट करता है कि क्या ध्वनि स्लाइडशो में अगले ध्वनि इवेंट तक लूप करेगी। |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। |
| [getAdvanceAfter()](#getAdvanceAfter--) | यह गुण निर्दिष्ट करता है कि क्या स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा। |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | यह गुण निर्दिष्ट करता है कि क्या स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा। |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | ट्रांज़िशन शुरू होने के बाद समय (मिलीसेकंड में) निर्दिष्ट करता है। |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | ट्रांज़िशन शुरू होने के बाद समय (मिलीसेकंड में) निर्दिष्ट करता है। |
| [getSpeed()](#getSpeed--) | वर्तमान स्लाइड से अगले पर ट्रांज़िशन करते समय उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। |
| [setSpeed(int value)](#setSpeed-int-) | वर्तमान स्लाइड से अगले पर ट्रांज़िशन करते समय उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। |
| [getValue()](#getValue--) | स्लाइड शो ट्रांज़िशन मान। |
| [getType()](#getType--) | ट्रांज़िशन का प्रकार। |
| [setType(int value)](#setType-int-) | ट्रांज़िशन का प्रकार। |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। |
| [getSoundName()](#getSoundName--) | ट्रांज़िशन की ध्वनि के लिए एक मानव-पाठनीय नाम निर्दिष्ट करता है। |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ट्रांज़िशन की ध्वनि के लिए एक मानव-पाठनीय नाम निर्दिष्ट करता है। |
| [getDuration()](#getDuration--) | स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता या सेट करता है। |
| [setDuration(int value)](#setDuration-int-) | स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता या सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो SlideShowTransition इंस्टेंस समान हैं या नहीं। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हेश फ़ंक्शन के रूप में कार्य करता है, जो हेशिंग एल्गोरिदम और हेश टेबल जैसी डेटा संरचनाओं में उपयोग के योग्य है। |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

एंबेडेड ऑडियो डेटा को लौटाता या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

**रिटर्न:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

एंबेडेड ऑडियो डेटा को लौटाता या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता या लौटाता है। पढ़ें/लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)।

**रिटर्न:**  
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता या लौटाता है। पढ़ें/लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

यह गुण निर्दिष्ट करता है कि क्या ध्वनि स्लाइडशो में अगले ध्वनि इवेंट तक लूप करेगी। पढ़ें/लिखें बूलियन।

**रिटर्न:**  
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

यह गुण निर्दिष्ट करता है कि क्या ध्वनि स्लाइडशो में अगले ध्वनि इवेंट तक लूप करेगी। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह गुण निर्दिष्ट नहीं है तो true मान माना जाता है। पढ़ें/लिखें बूलियन।

**रिटर्न:**  
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

निर्दिष्ट करता है कि क्या माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह गुण निर्दिष्ट नहीं है तो true मान माना जाता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

यह गुण निर्दिष्ट करता है कि क्या स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा। पढ़ें/लिखें बूलियन।

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग सेट है या नहीं
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
public final void setAdvanceAfter(boolean value)
```

यह गुण निर्दिष्ट करता है कि क्या स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा। पढ़ें/लिखें बूलियन।

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहला स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग सेट है या नहीं
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
public final long getAdvanceAfterTime()
```

ट्रांज़िशन शुरू होने के बाद समय (मिलीसेकंड में) निर्दिष्ट करता है। यह सेटिंग advClick गुण के साथ उपयोग की जा सकती है। यदि यह गुण निर्दिष्ट नहीं है तो यह मान लिया जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें/लिखें लॉंग।

**रिटर्न:**  
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

ट्रांज़िशन शुरू होने के बाद समय (मिलीसेकंड में) निर्दिष्ट करता है। यह सेटिंग advClick गुण के साथ उपयोग की जा सकती है। यदि यह गुण निर्दिष्ट नहीं है तो यह मान लिया जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें/लिखें लॉंग।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

वर्तमान स्लाइड से अगले पर ट्रांज़िशन करते समय उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। पढ़ें/लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**रिटर्न:**  
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

वर्तमान स्लाइड से अगले पर ट्रांज़िशन करते समय उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। पढ़ें/लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

स्लाइड शो ट्रांज़िशन मान। केवल-पढ़ने योग्य [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)।

**रिटर्न:**  
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

ट्रांज़िशन का प्रकार। पढ़ें/लिखें [TransitionType](../../com.aspose.slides/transitiontype)।

**रिटर्न:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

ट्रांज़िशन का प्रकार। पढ़ें/लिखें [TransitionType](../../com.aspose.slides/transitiontype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। यदि यह गुण true पर सेट किया जाता है तो जनरेटिंग एप्लिकेशन को इस ध्वनि के लिए निर्दिष्ट नाम गुण की जाँच करने के लिए सतर्क किया जाता है और फिर आवश्यकता अनुसार कस्टम नाम या UI प्रदर्शित किया जा सकता है। पढ़ें/लिखें बूलियन।

**रिटर्न:**  
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। यदि यह गुण true पर सेट किया जाता है तो जनरेटिंग एप्लिकेशन को इस ध्वनि के लिए निर्दिष्ट नाम गुण की जाँच करने के लिए सतर्क किया जाता है और फिर आवश्यकता अनुसार कस्टम नाम या UI प्रदर्शित किया जा सकता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

ट्रांज़िशन की ध्वनि के लिए एक मानव-पाठनीय नाम निर्दिष्ट करता है। ध्वनि ( #getSound.getSound/#setSound(IAudio).setSound(IAudio) ) प्रॉपर्टी को ध्वनि नाम प्राप्त या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ें/लिखें स्ट्रिंग।

**रिटर्न:**  
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

ट्रांज़िशन की ध्वनि के लिए एक मानव-पाठनीय नाम निर्दिष्ट करता है। ध्वनि ( #getSound.getSound/#setSound(IAudio).setSound(IAudio) ) प्रॉपर्टी को ध्वनि नाम प्राप्त या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ें/लिखें स्ट्रिंग।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता या सेट करता है। पढ़ें/लिखें int।

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the #getSpeed.getSpeed/#setSpeed(int).setSpeed(int) property and the transition type.

**रिटर्न:**  
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

स्लाइड ट्रांज़िशन प्रभाव की अवधि को मिलीसेकंड में प्राप्त करता या सेट करता है। पढ़ें/लिखें int।

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the #getSpeed.getSpeed/#setSpeed(int).setSpeed(int) property and the transition type.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो SlideShowTransition इंस्टेंस समान हैं या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने वाला SlideShowTransition। |

**रिटर्न:**  
boolean - **true** यदि निर्दिष्ट SlideShowTransition वर्तमान SlideShowTransition के बराबर है; अन्यथा **false**।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हेश फ़ंक्शन के रूप में कार्य करता है, जो हेशिंग एल्गोरिदम और हेश टेबल जैसी डेटा संरचनाओं में उपयोग के योग्य है।

**रिटर्न:**  
int - 23454

Overriden to make compiler happy. Always returns constant because object is mutable.