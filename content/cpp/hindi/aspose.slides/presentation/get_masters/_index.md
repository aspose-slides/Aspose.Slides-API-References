---
title: get_Masters()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पढ़ने-योग्य IMasterSlideCollection.
type: docs
weight: 118
url: /hi/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() मेथड


प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पढ़ने-योग्य [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## टिप्पणियाँ


निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint [Presentation](../) के Master [Slides](../../) में [Images](../../images/) कैसे जोड़ें। 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint [Presentation](../) की मास्टर स्लाइड का पृष्ठभूमि रंग कैसे बदलें। 
```cpp
// प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंटिएट करें
auto pres = System::MakeObject<Presentation>();

// मास्टर ISlide की पृष्ठभूमि रंग को फ़ॉरेस्ट ग्रीन सेट करें
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// प्रेजेंटेशन को डिस्क पर लिखें
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint [Presentation](../) में स्लाइड लेआउट कैसे जोड़ें। 
```cpp
// प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंटिएट करें
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// लेआउट स्लाइड प्रकार द्वारा खोजने का प्रयास करें
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // स्थिति जब प्रेजेंटेशन में कुछ प्रकार के लेआउट नहीं होते हैं।
    // प्रेजेंटेशन फ़ाइल में केवल ब्लैंक्स और कस्टम लेआउट प्रकार होते हैं।
    // लेकिन कस्टम प्रकार वाले लेआउट स्लाइड्स के अलग-अलग स्लाइड नाम होते हैं,
    // जैसे "Title", "Title and Content" आदि। और इनका उपयोग करना संभव है
    // नामों को लेआउट स्लाइड चयन के लिए।
    // इसके अलावा प्लेसहोल्डर शेप प्रकारों के सेट का उपयोग करना संभव है। उदाहरण के लिए,
    // टाइटल स्लाइड में केवल टाइटल प्लेसहोल्डर प्रकार होना चाहिए, आदि।
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// जोड़े गए लेआउट स्लाइड के साथ खाली स्लाइड जोड़ रहे हैं
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// प्रेजेंटेशन को सहेजें
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMasterSlideCollection](../../imasterslidecollection/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)