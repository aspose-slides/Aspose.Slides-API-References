---
title: InsertClone()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट मास्टर स्लाइड की एक प्रति को संग्रह की निर्दिष्ट स्थिति में डालता है। जुड़े लेआउट स्लाइड्स भी कॉपी की जाएँगी।
type: docs
weight: 105
url: /hi/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) विधि


एक निर्दिष्ट मास्टर स्लाइड की प्रतिलिपि को संग्रह के निर्दिष्ट स्थान पर डालता है। जुड़ी हुई लेआउट स्लाइड्स भी कॉपी की जाएँगी।

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नया स्लाइड का अनुक्रमांक। |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### Return Value

डाली गई मास्टर स्लाइड।

## टिप्पणी



निम्न उदाहरण दिखाता है कि कैसे किसी अन्य PowerPoint [Presentation](../../presentation/) में मास्टर स्लाइड को क्लोन किया जाए। 
```cpp
// स्रोत प्रस्तुति फ़ाइल लोड करने के लिए Presentation क्लास का उदाहरण बनाएँ
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// गंतव्य प्रस्तुति (जहाँ स्लाइड क्लोन की जानी है) के लिए Presentation क्लास का उदाहरण बनाएँ
auto destPres = System::MakeObject<Presentation>();

// स्रोत प्रस्तुति में स्लाइड्स के संग्रह से ISlide का उदाहरण बनाएँ, साथ ही
// मुख्य स्लाइड
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// गंतव्य प्रस्तुति की मास्टर स्लाइड्स प्राप्त करें
auto masters = destPres->get_Masters();
// स्रोत प्रस्तुति से इच्छित मास्टर स्लाइड को गंतव्य प्रस्तुति की मास्टर संग्रह में क्लोन करें
// गंतव्य प्रस्तुति
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// गंतव्य प्रस्तुति में स्लाइड्स का संग्रह
auto slides = destPres->get_Slides();
// स्रोत स्लाइड को गंतव्य स्लाइड्स संग्रह में क्लोन करें।
slides->AddClone(sourceSlide, iSlide, true);
// गंतव्य प्रस्तुति को डिस्क पर सहेजें
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)