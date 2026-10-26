---
title: set_Rewind()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह गुण निर्धारित करता है कि प्रभाव समाप्त होने पर पुनः चलाया जाएगा या नहीं। लिखें bool.
type: docs
weight: 326
url: /hi/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) विधि


यह गुण निर्धारित करता है कि प्रभाव समाप्त होने पर पुनः चलाया जाएगा या नहीं। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## संबंधित देखें

* क्लास [ITiming](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)