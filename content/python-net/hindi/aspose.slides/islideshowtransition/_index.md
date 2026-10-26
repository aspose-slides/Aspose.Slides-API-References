---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islideshowtransition/
---
## ISlideShowTransition क्लास

Represents slide show transition.

The ISlideShowTransition type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound/) | एम्बेडेड ऑडियो डेटा को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)। |
| [`sound_mode`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound_mode/) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता है या प्राप्त करता है।<br/>            पढ़ें/लिखें [`TransitionSoundMode`](/slides/python-net/hi/aspose.slides.slideshow/transitionsoundmode)। |
| [`sound_loop`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound_loop/) | यह गुण निर्धारित करता है कि ध्वनि अगली ध्वनि घटना उत्पन्न होने तक लूप होगा या नहीं<br/>            स्लाइडशो में।<br/>            पढ़ें/लिखें **bool**। |
| [`advance_on_click`](/slides/python-net/hi/aspose.slides/islideshowtransition/advance_on_click/) | निर्दिष्ट करता है कि माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह गुण निर्दिष्ट नहीं है तो true मान माना जाता है।<br/>            पढ़ें/लिखें **bool**। |
| [`advance_after`](/slides/python-net/hi/aspose.slides/islideshowtransition/advance_after/) | यह गुण निर्धारित करता है कि एक निश्चित समय के बाद स्लाइडशो अगली स्लाइड पर जाएगा या नहीं।<br/>            पढ़ें/लिखें **bool**। |
| [`advance_after_time`](/slides/python-net/hi/aspose.slides/islideshowtransition/advance_after_time/) | ट्रांज़िशन शुरू होने के बाद मिलिसेकंड में समय निर्धारित करता है। यह सेटिंग<br/>            advClick गुण के साथ उपयोग की जा सकती है। यदि यह गुण निर्दिष्ट नहीं है<br/>            तो यह मान लिया जाता है कि कोई ऑटो-एडवांस नहीं होगा।<br/>            पढ़ें/लिखें **int**। |
| [`speed`](/slides/python-net/hi/aspose.slides/islideshowtransition/speed/) | वर्तमान स्लाइड से अगली स्लाइड पर ट्रांज़िशन करते समय उपयोग की जाने वाली गति निर्धारित करता है।<br/>            पढ़ें/लिखें [`TransitionSpeed`](/slides/python-net/hi/aspose.slides.slideshow/transitionspeed)। |
| [`value`](/slides/python-net/hi/aspose.slides/islideshowtransition/value/) | स्लाइड शो ट्रांज़िशन मान।<br/>            केवल पढ़ने योग्य [`ITransitionValueBase`](/slides/python-net/hi/aspose.slides.slideshow/itransitionvaluebase)। |
| [`type`](/slides/python-net/hi/aspose.slides/islideshowtransition/type/) | ट्रांज़िशन का प्रकार।<br/>            पढ़ें/लिखें [`TransitionType`](/slides/python-net/hi/aspose.slides.slideshow/transitiontype)। |
| [`sound_is_built_in`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound_is_built_in/) | निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। यदि यह गुण true पर सेट है तो<br/>            जनरेटिंग एप्लिकेशन को इस ध्वनि के लिए निर्दिष्ट नाम गुण को बिल्ट-इन ध्वनियों की सूची में जांचने के लिए चेतावनी दी जाती है और फिर आवश्यकतानुसार कस्टम नाम या UI प्रदर्शित किया जा सकता है।<br/>            पढ़ें/लिखें **bool**। |
| [`sound_name`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound_name/) | ट्रांज़िशन ध्वनि के लिए मानव-पढ़ने योग्य नाम निर्धारित करता है। ध्वनि नाम प्राप्त करने या सेट करने के लिए [`ISlideShowTransition.sound`](/slides/python-net/hi/aspose.slides/islideshowtransition/sound) प्रॉपर्टी को असाइन करना आवश्यक है।<br/>            पढ़ें/लिखें **str**। |
| [`duration`](/slides/python-net/hi/aspose.slides/islideshowtransition/duration/) | स्लाइड ट्रांज़िशन प्रभाव की अवधि मिलिसेकंड में प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **int**। |

### संबंधित
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)