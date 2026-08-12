---
title: Equals()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान हैं यदि सभी आकार, शैलियां, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे वर्तमान तिथि मान Date Placeholder, को ध्यान नहीं दिया जाता।
type: docs
weight: 170
url: /hi/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) मेथड

निर्धारित करता है कि दो [IBaseSlide](../../ibaseslide/) उदाहरण समान हैं या नहीं। लौटाई गई मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना की जाती है। दो स्लाइड समान मानी जाती हैं यदि सभी आकार, शैली, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मानों, जैसे SlideId, और गतिशील सामग्री, जैसे वर्तमान तिथि मान Date [Placeholder](../../placeholder/) को ध्यान में नहीं रखा जाता।

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | वर्तमान [IBaseSlide](../../ibaseslide/) के साथ तुलना करने के लिए [IBaseSlide](../../ibaseslide/)। |

### वापसी मान

**true** यदि निर्दिष्ट [IBaseSlide](../../ibaseslide/) वर्तमान [IBaseSlide](../../ibaseslide/) के बराबर है; अन्यथा, **false**.

## टिप्पणी

निम्न उदाहरण दिखाता है कि दो स्लाइड की तुलना कैसे करें।
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IBaseSlide](../../ibaseslide/)
* क्लास [BaseSlide](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)