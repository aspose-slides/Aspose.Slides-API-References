---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा। bool लिखें।
type: docs
weight: 144
url: /hi/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) विधि


यह गुण निर्दिष्ट करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// पहले स्लाइड के लिए इफ़ेक्ट्स क्रम प्राप्त करता है
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// मुख्य क्रम का पहला इफ़ेक्ट प्राप्त करता है।
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// इफ़ेक्ट की टाइमिंग/रिपीट को "स्लाइड के अंत तक" बदलता है
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## संबंधित देखें

* क्लास [ITiming](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)