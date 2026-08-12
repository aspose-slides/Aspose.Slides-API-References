---
title: get_Placeholder()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने-योग्य IPlaceholder.
type: docs
weight: 14
url: /hi/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() विधि


एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने-योग्य [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## टिप्पणियाँ


निम्न उदाहरण दिखाता है कि [Placeholder](../../placeholder/) में Text कैसे बदलें। 
```cpp
// एक Presentation क्लास का इंस्टेंस बनाता है
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// पहले स्लाइड को एक्सेस करता है
auto slide = pres->get_Slides()->idx_get(0);

// प्लेसहोल्डर खोजने के लिए शैप्स पर इटरेट करता है
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // प्रत्येक प्लेसहोल्डर में टेक्स्ट बदलता है
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// प्रस्तुति को डिस्क पर सहेजता है
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 निम्न उदाहरण दिखाता है कि [Placeholder](../../placeholder/) में Prompt Text कैसे सेट करें। 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPlaceholder](../../iplaceholder/)
* क्लास [Shape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)