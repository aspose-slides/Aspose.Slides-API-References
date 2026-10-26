---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: यह गुण निर्धारित करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा। लिखें bool.
type: docs
weight: 144
url: /hi/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) मेथड


यह गुण निर्धारित करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा। लिखें **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## देखें

* क्लास [Timing](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)