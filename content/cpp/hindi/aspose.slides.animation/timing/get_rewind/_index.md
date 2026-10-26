---
title: get_Rewind()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह विशेषता निर्धारित करती है कि प्रभाव प्ले होने के बाद पुनः चलाया जाएगा या नहीं। पढ़ें bool.
type: docs
weight: 235
url: /hi/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() विधि


यह विशेषता निर्धारित करती है कि प्रभाव प्ले होने के बाद पुनः चलाया जाएगा या नहीं। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड के लिए इफ़ेक्ट्स क्रम प्राप्त करें
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// मुख्य क्रम के पहले इफ़ेक्ट को प्राप्त करें।
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// इफ़ेक्ट का Timing/Rewind सक्रिय करें।
effect->get_Timing()->set_Rewind(true);
```

## संबंधित देखें

* वर्ग [Timing](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)