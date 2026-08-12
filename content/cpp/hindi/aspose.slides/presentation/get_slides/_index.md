---
title: get_Slides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेज़ेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य ISlideCollection.
type: docs
weight: 53
url: /hi/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() विधि

Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../) में स्लाइड्स की पृष्ठभूमि रंग कैसे सेट किया जाता है। 
```cpp
// प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// पहली ISlide की पृष्ठभूमि रंग को नीला सेट करें
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../) में स्लाइड्स की पृष्ठभूमि छवि कैसे सेट की जाती है। 
```cpp
// प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// छवि के साथ पृष्ठभूमि सेट करें
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// चित्र सेट करें
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// प्रस्तुति की छवियों संग्रह में छवि जोड़ें
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// प्रस्तुति को डिस्क पर लिखें
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दिखाता है कि स्लाइड ट्रांज़िशन [Presentation](../) कैसे जोड़ा जाता है। 
```cpp
// स्रोत प्रस्तुति फ़ाइल को लोड करने के लिए Presentation क्लास का उदाहरण बनाएं
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// स्लाइड 1 पर सर्कल प्रकार का ट्रांज़िशन लागू करें
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// स्लाइड 2 पर कॉम्ब प्रकार का ट्रांज़िशन लागू करें
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// प्रस्तुति को डिस्क पर लिखें
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दिखाता है कि उन्नत स्लाइड ट्रांज़िशन कैसे जोड़ा जाता है। 
```cpp
// प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// स्लाइड 1 पर सर्कल प्रकार का ट्रांज़िशन लागू करें
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// ट्रांज़िशन समय को 3 सेकंड सेट करें
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// स्लाइड 2 पर कॉम्ब प्रकार का ट्रांज़िशन लागू करें
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// ट्रांज़िशन समय को 5 सेकंड सेट करें
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// स्लाइड 3 पर ज़ूम प्रकार का ट्रांज़िशन लागू करें
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// ट्रांज़िशन समय को 7 सेकंड सेट करें
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// प्रस्तुति को डिस्क पर लिखें
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlideCollection](../../islidecollection/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)