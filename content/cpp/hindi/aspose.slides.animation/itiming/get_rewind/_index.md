---
title: get_Rewind()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: यह विशेषता निर्धारित करती है कि प्रभाव समाप्त होने पर रिवाइंड होगा या नहीं। पढ़ें bool.
type: docs
weight: 313
url: /hi/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() विधि

यह विशेषता निर्धारित करती है कि प्रभाव समाप्त होने पर रिवाइंड होगा या नहीं। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## टिप्पणियाँ

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## देखें

* क्लास [ITiming](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)