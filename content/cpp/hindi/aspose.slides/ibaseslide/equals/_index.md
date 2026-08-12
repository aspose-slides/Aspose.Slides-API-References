---
title: Equals()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि दो IBaseSlide उदाहरण बराबर हैं या नहीं। रिटर्न वैल्यू स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना की जाती है। दो स्लाइड्स बराबर होती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मानों, जैसे SlideId, और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता।
type: docs
weight: 183
url: /hi/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) विधि


निर्धारित करता है कि दो [IBaseSlide](../) उदाहरण समतुल्य हैं या नहीं। रिटर्न वैल्यू स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना की जाती है। दो स्लाइड्स समान होती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मूल्यों, जैसे SlideId, तथा गतिशील सामग्री, जैसे Date [Placeholder](../../placeholder/) में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता।

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | वर्तमान [IBaseSlide](../) के साथ तुलना करने हेतु [IBaseSlide](../)। |

### रिटर्न मान

**true** यदि निर्दिष्ट [IBaseSlide](../) वर्तमान [IBaseSlide](../) के बराबर है; अन्यथा, **false**.

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IBaseSlide](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)