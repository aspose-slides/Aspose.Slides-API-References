---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्दिष्ट करती है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। लिखें bool।
type: docs
weight: 170
url: /hi/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) विधि

This attribute specifies if the effect will repeat until the next click. Write **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## संबंधित देखें

* क्लास [ITiming](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)