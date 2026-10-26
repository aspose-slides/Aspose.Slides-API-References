---
title: SlideShowTransition
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

Represents slide show transition.

## विधियां

| विधि | विवरण |
| --- | --- |
| [getSound()](#getSound--) | एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | एंबेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। |
| [getSoundMode()](#getSoundMode--) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या प्राप्त करता है। |
| [setSoundMode(int value)](#setSoundMode-int-) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या प्राप्त करता है। |
| [getSoundLoop()](#getSoundLoop--) | यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो में अगली साउंड इवेंट होने तक साउंड लूप करेगा या नहीं। |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो में अगली साउंड इवेंट होने तक साउंड लूप करेगा या नहीं। |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | निर्धारित करता है कि माउस क्लिक से स्लाइड आगे बढ़ेगा या नहीं। |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | निर्धारित करता है कि माउस क्लिक से स्लाइड आगे बढ़ेगा या नहीं। |
| [getAdvanceAfter()](#getAdvanceAfter--) | यह एट्रिब्यूट निर्दिष्ट करता है कि एक निश्चित समय के बाद स्लाइडशो अगली स्लाइड पर जाएगा या नहीं। |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | यह एट्रिब्यूट निर्धारित करता है कि एक निश्चित समय के बाद स्लाइडशो अगली स्लाइड पर जाएगा या नहीं। |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | मिलीसेकंड में वह समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | मिलीसेकंड में वह समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। |
| [getSpeed()](#getSpeed--) | वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। |
| [setSpeed(int value)](#setSpeed-int-) | वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। |
| [getValue()](#getValue--) | स्लाइडशो ट्रांज़िशन मान। |
| [getType()](#getType--) | ट्रांज़िशन का प्रकार। |
| [setType(int value)](#setType-int-) | ट्रांज़िशन का प्रकार। |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | निर्धारित करता है कि यह साउंड बिल्ट-इन साउंड है या नहीं। |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | निर्धारित करता है कि यह साउंड बिल्ट-इन साउंड है या नहीं। |
| [getSoundName()](#getSoundName--) | ट्रांज़िशन के साउंड के लिए एक मानव-पठन योग्य नाम निर्दिष्ट करता है। |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | ट्रांज़िशन के साउंड के लिए एक मानव-पठन योग्य नाम निर्दिष्ट करता है। |
| [getDuration()](#getDuration--) | स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि मिलीसेकंड में प्राप्त या सेट करता है। |
| [setDuration(int value)](#setDuration-int-) | स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि मिलीसेकंड में प्राप्त या सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो SlideShowTransition इंस्टेंस बराबर हैं या नहीं। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिये उपयुक्त है। |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**वापसी:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या प्राप्त करता है। पढ़ें/लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**वापसी:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या प्राप्त करता है। पढ़ें/लिखें [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो में अगली साउंड इवेंट होने तक साउंड लूप करेगा या नहीं। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो में अगली साउंड इवेंट होने तक साउंड लूप करेगा या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

निर्दिष्ट करता है कि माउस क्लिक से स्लाइड आगे बढ़ेगा या नहीं। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो मान true माना जाता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

निर्दिष्ट करता है कि माउस क्लिक से स्लाइड आगे बढ़ेगा या नहीं। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो मान true माना जाता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

यह एट्रिब्यूट निर्दिष्ट करता है कि एक निश्चित समय के बाद स्लाइडशो अगली स्लाइड पर जाएगा या नहीं। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहले स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग चेक किया गया है या नहीं
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After टाइम मान प्राप्त करें
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

यह एट्रिब्यूट निर्दिष्ट करता है कि एक निश्चित समय के बाद स्लाइडशो अगली स्लाइड पर जाएगा या नहीं। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // पहला स्लाइड ट्रांज़िशन प्राप्त करें
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // जांचें कि Advance Slide After फ़्लैग चेक किया गया है
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After टाइम मान प्राप्त करें
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

मिलीसेकंड में वह समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। यह सेटिंग advClick एट्रिब्यूट के साथ मिलाकर उपयोग की जा सकती है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो यह माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें/लिखें लॉन्ग।

**वापसी:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

मिलीसेकंड में वह समय निर्दिष्ट करता है जिसके बाद ट्रांज़िशन शुरू होना चाहिए। यह सेटिंग advClick एट्रिब्यूट के साथ मिलाकर उपयोग की जा सकती है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो यह माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें/लिखें लॉन्ग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। पढ़ें/लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**वापसी:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति को निर्दिष्ट करता है। पढ़ें/लिखें [TransitionSpeed](../../com.aspose.slides/transitionspeed)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

स्लाइडशो ट्रांज़िशन मान। केवल पढ़ने योग्य [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)।

**वापसी:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

ट्रांज़िशन का प्रकार। पढ़ें/लिखें [TransitionType](../../com.aspose.slides/transitiontype)।

**वापसी:**
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

निर्दिष्ट करता है कि यह साउंड बिल्ट-इन साउंड है या नहीं। यदि यह एट्रिब्यूट true पर सेट किया जाता है तो जनरेटिंग एप्लिकेशन को इस साउंड के लिए उसके बिल्ट-इन साउंड सूची में निर्दिष्ट नाम एट्रिब्यूट की जाँच करने के लिए सचेत किया जाता है और आवश्यकतानुसार कस्टम नाम या यूआई प्रदर्शित किया जा सकता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

निर्दिष्ट करता है कि यह साउंड बिल्ट-इन साउंड है या नहीं। यदि यह एट्रिब्यूट true पर सेट किया जाता है तो जनरेटिंग एप्लिकेशन को इस साउंड के लिए उसके बिल्ट-इन साउंड सूची में निर्दिष्ट नाम एट्रिब्यूट की जाँच करने के लिए सचेत किया जाता है और आवश्यकतानुसार कस्टम नाम या यूआई प्रदर्शित किया जा सकता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

ट्रांज़िशन के साउंड के लिए एक मानव-पठन योग्य नाम निर्दिष्ट करता है। Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) प्रॉपर्टी को साउंड नाम प्राप्त करने या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ें/लिखें स्ट्रिंग।

**वापसी:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

ट्रांज़िशन के साउंड के लिए एक मानव-पठन योग्य नाम निर्दिष्ट करता है। Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) प्रॉपर्टी को साउंड नाम प्राप्त करने या सेट करने के लिए असाइन किया जाना चाहिए। पढ़ें/लिखें स्ट्रिंग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि मिलीसेकंड में प्राप्त या सेट करता है। पढ़ें/लिखें इंट।

PresentationML स्कीमा में p:transition तत्व के p14:dur एट्रिब्यूट के अनुरूप है। यदि सेट नहीं किया गया है, तो अवधि को \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) प्रॉपर्टी और ट्रांज़िशन प्रकार के आधार पर स्वतः निर्धारित किया जाता है।

**वापसी:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि मिलीसेकंड में प्राप्त या सेट करता है। पढ़ें/लिखें इंट।

PresentationML स्कीमा में p:transition तत्व के p14:dur एट्रिब्यूट के अनुरूप है। यदि सेट नहीं किया गया है, तो अवधि को \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) प्रॉपर्टी और ट्रांज़िशन प्रकार के आधार पर स्वतः निर्धारित किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो SlideShowTransition इंस्टेंस बराबर हैं या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | The SlideShowTransition to compare with the current SlideShowTransition. |

**वापसी:**
बूलियन -  **true**  यदि निर्दिष्ट SlideShowTransition वर्तमान SlideShowTransition के बराबर है; अन्यथा,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिये उपयुक्त है।

**वापसी:**
int - 23454

--------------------

कम्पाइलर को खुश करने के लिये ओवरराइड किया गया। हमेशा स्थिर मान लौटाता है क्योंकि ऑब्जेक्ट परिवर्तनशील है।