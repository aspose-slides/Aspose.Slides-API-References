---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides के लिए C++ एपीआई संदर्भ
description: यह विशेषता निर्धारित करती है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें bool.
type: docs
weight: 131
url: /hi/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() मेथड

This attribute specifies if the effect will repeat until the end of the slide. Read **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
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

## देखें भी

* क्लास [Timing](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)