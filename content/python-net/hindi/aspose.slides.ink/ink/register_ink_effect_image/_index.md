---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
इंक ब्रश के लिए दृश्य प्रभावों का अनुकरण करने हेतु उपयोग की जाने कस्टम छवियों के संग्रह में एक छवि को रजिस्टर करता है।
            इन छवियों का उपयोग तब किया जाता है जब विशेष [`InkEffectType`](/slides/python-net/hi/aspose.slides.ink/inkeffecttype) मानों के साथ इंक रेंडर किया जाता है,
            जैसे कि Galaxy, Rainbow, आदि। अपनी स्वयं की छवियों को प्रदान करके, आप प्रत्येक इंक प्रभाव के प्रकट होने के तरीके को नियंत्रित कर सकते हैं।


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/hi/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/hi/aspose.slides/iimage) |  |

### टिप्पणी

यह विधि डिफ़ॉल्ट इंक प्रभाव बनावटों को उपयोगकर्ता-परिभाषित बनावटों के साथ बदलने की अनुमति देती है, जो विशेष रूप से तब उपयोगी होती है जब डिफ़ॉल्ट संसाधनों पर लाइसेंसिंग द्वारा प्रतिबंध होता है या रनटाइम में उपलब्ध नहीं होते। प्रत्येक रजिस्टर्ड मान जोड़े को एक [`InkEffectType`](/slides/python-net/hi/aspose.slides.ink/inkeffecttype) मान को संबंधित [`IImage`](/slides/python-net/hi/aspose.slides/iimage) ऑब्जेक्ट (उदा., Bitmap, या Aspose इमेज इंटरफ़ेस) के साथ संबद्ध करना चाहिए।



### संबंधित देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`Ink`](/slides/python-net/hi/aspose.slides.ink/ink)
* एनीयुमरेशन [`InkEffectType`](/slides/python-net/hi/aspose.slides.ink/inkeffecttype)
* मॉड्यूल [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)