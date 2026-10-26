---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह एट्रिब्यूट यह निर्दिष्ट करता है कि प्रभाव अगली क्लिक तक दोहराया जाएगा। Read bool.
type: docs
weight: 157
url: /hi/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() विधि


यह एट्रिब्यूट यह निर्दिष्ट करता है कि प्रभाव अगली क्लिक होने तक दोहराया जाएगा। Read **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## टिप्पणियां



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
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)