---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड की सामग्री को एक EMF फ़ाइल के रूप में सहेजता है।
type: docs
weight: 170
url: /hi/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) विधि


स्लाइड की सामग्री को एक EMF फ़ाइल के रूप में सहेजता है।

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लक्षित स्ट्रीम |
## टिप्पणी



निम्नलिखित कोड उदाहरण दर्शाता है कि कैसे PowerPoint प्रस्तुति की पहली स्लाइड को एक मेटा फ़ाइल में परिवर्तित किया जाता है। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// पहले स्लाइड को एक मेटा फ़ाइल के रूप में सहेजता है
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [Slide](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)