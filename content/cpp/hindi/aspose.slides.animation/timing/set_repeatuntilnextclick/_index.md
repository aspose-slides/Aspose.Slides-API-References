---
title: set_RepeatUntilNextClick()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: यह एट्रिब्यूट निर्दिष्ट करता है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। लिखें bool.
type: docs
weight: 170
url: /hi/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) विधि

यह एट्रिब्यूट निर्दिष्ट करता है कि प्रभाव अगली क्लिक तक दोहराया जाएगा या नहीं। लिखें **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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

## देखें भी

* क्लास [Timing](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)