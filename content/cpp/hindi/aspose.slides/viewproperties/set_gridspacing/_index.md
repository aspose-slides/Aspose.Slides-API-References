---
title: set_GridSpacing()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: ग्रिड स्पेसिंग सेट करता है जिसका उपयोग प्रेजेंटेशन दस्तावेज़ के आधार ग्रिड के लिए पॉइंट्स में किया जाना चाहिए। float लिखें।
type: docs
weight: 105
url: /hi/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) विधि


प्रेजेंटेशन दस्तावेज़ के आधार पर ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट्स में सेट करता है। **float** लिखें।

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## टिप्पणियाँ


ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान रेंज 1 mm (2.8349607 पॉइंट्स) से 2 इंच (144 पॉइंट्स) तक है। 

निम्नलिखित नमूना कोड दिखाता है कि PowerPoint प्रेज़ेंटेशन में ग्रिड स्पेसिंग को कैसे बदलें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## देखें

* वर्ग [ViewProperties](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)