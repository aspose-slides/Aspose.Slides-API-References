---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह गुण यह निर्धारित करता है कि प्रभाव स्लाइड के अंत तक दोहराया जाएगा या नहीं। पढ़ें bool.
type: docs
weight: 131
url: /hi/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() विधि


यह गुण निर्धारित करता है कि क्या प्रभाव स्लाइड के अंत तक दोहराया जाएगा। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
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

* क्लास [ITiming](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)