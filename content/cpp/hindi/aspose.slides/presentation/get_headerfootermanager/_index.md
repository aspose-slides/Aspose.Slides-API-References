---
title: get_HeaderFooterManager()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वास्तविक HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /hi/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() विधि


वास्तविक HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## टिप्पणियाँ


निम्न उदाहरण दर्शाता है कि PowerPoint [Presentation](../) के [Slide](../../slide/) के भीतर फुटर की दृश्यता कैसे सेट की जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// स्लाइड फ़ूटर प्लेसहोल्डर अनुपलब्ध होने को दर्शाने के लिए Property IsFooterVisible का उपयोग किया जाता है।
if (!headerFooterManager->get_IsFooterVisible())
{
    // स्लाइड फ़ूटर प्लेसहोल्डर को दृश्यमान बनाने के लिए Method SetFooterVisibility का उपयोग किया जाता है।
    headerFooterManager->SetFooterVisibility(true);
}

// स्लाइड पेज नंबर प्लेसहोल्डर अनुपलब्ध होने को दर्शाने के लिए Property IsSlideNumberVisible का उपयोग किया जाता है।
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // स्लाइड पेज नंबर प्लेसहोल्डर को दृश्यमान बनाने के लिए Method SetSlideNumberVisibility का उपयोग किया जाता है।
    headerFooterManager->SetSlideNumberVisibility(true);
}

// स्लाइड तिथि-समय प्लेसहोल्डर अनुपलब्ध होने को दर्शाने के लिए Property IsDateTimeVisible का उपयोग किया जाता है।
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // स्लाइड तिथि-समय प्लेसहोल्डर को दृश्यमान बनाने के लिए Method SetFooterVisibility का उपयोग किया जाता है।
    headerFooterManager->SetDateTimeVisibility(true);
}

// स्लाइड फ़ूटर प्लेसहोल्डर पर टेक्स्ट सेट करने के लिए Method SetFooterText का उपयोग किया जाता है।
headerFooterManager->SetFooterText(u"Footer text");
// स्लाइड तिथि-समय प्लेसहोल्डर पर टेक्स्ट सेट करने के लिए Method SetDateTimeText का उपयोग किया जाता है।
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 निम्न उदाहरण दर्शाता है कि [Slide](../../slide/) के भीतर चाइल्ड फुटर की दृश्यता कैसे सेट की जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Method SetFooterAndChildFootersVisibility का उपयोग एक मास्टर स्लाइड और सभी चाइल्ड फ़ूटर प्लेसहोल्डर को दृश्यमान बनाने के लिए किया जाता है।
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Method SetSlideNumberAndChildSlideNumbersVisibility का उपयोग एक मास्टर स्लाइड और सभी चाइल्ड पेज नंबर प्लेसहोल्डर को दृश्यमान बनाने के लिए किया जाता है।
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Method SetDateTimeAndChildDateTimesVisibility का उपयोग एक मास्टर स्लाइड और सभी चाइल्ड तिथि-समय प्लेसहोल्डर को दृश्यमान बनाने के लिए किया जाता है।
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Method SetFooterAndChildFootersText का उपयोग मास्टर स्लाइड और सभी चाइल्ड फ़ूटर प्लेसहोल्डर पर टेक्स्ट सेट करने के लिए किया जाता है।
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Method SetDateTimeAndChildDateTimesText का उपयोग मास्टर स्लाइड और सभी चाइल्ड तिथि-समय प्लेसहोल्डर पर टेक्स्ट सेट करने के लिए किया जाता है।
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)