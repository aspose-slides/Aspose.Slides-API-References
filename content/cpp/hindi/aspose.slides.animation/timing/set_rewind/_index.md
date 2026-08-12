---
title: set_Rewind()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह एट्रिब्यूट निर्दिष्ट करता है कि प्रभाव प्ले होने के बाद रीवाइंड होगा या नहीं। लिखें bool.
type: docs
weight: 248
url: /hi/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) मेथड

यह एट्रिब्यूट निर्दिष्ट करता है कि प्रभाव प्ले करने के बाद रीवाइंड होगा या नहीं। लिखें **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## टिप्पणियाँ

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
// पहली स्लाइड के लिए इफ़ेक्ट्स सीक्वेंस प्राप्त करें
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
 // मुख्य सीक्वेंस का पहला इफ़ेक्ट प्राप्त करें।
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
 // इफ़ेक्ट का टाइमिंग/रीवाइंड चालू करें।
effect->get_Timing()->set_Rewind(true);
```

## संबंधित

* क्लास [Timing](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)