---
title: set_GridSpacing()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग की जानी वाली ग्रिड स्पेसिंग को पॉइंट्स में सेट करता है। float लिखें।
type: docs
weight: 105
url: /hi/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) विधि


प्रेजेंटेशन दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग की जानी वाली ग्रिड स्पेसिंग को पॉइंट्स में सेट करता है। **float** लिखें।

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## टिप्पणियाँ


ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान सीमा 1 मिमी (2.8349607 पॉइंट्स) से 2 इंच (144 पॉइंट्स) तक है। 

निम्नलिखित नमूना कोड दिखाता है कि PowerPoint प्रेजेंटेशन में ग्रिड स्पेसिंग कैसे बदलें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [IViewProperties](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)