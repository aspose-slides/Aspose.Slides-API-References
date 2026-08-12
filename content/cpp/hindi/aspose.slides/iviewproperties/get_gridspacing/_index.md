---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति दस्तावेज़ के नीचे ग्रिड के लिए उपयोग किया जाने वाला ग्रिड स्पेसिंग पॉइंट्स में लौटाता है। float पढ़ें।
type: docs
weight: 92
url: /hi/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() विधि

प्रस्तुति दस्तावेज़ के नीचे ग्रिड के लिए उपयोग किया जाने वाला ग्रिड स्पेसिंग पॉइंट्स में लौटाता है। **float** पढ़ें।

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## टिप्पणियाँ

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होनी चाहिए। सामान्य मान सीमा 1 mm (2.8349607 पॉइंट्स) से 2 इंच (144 पॉइंट्स) तक होती है।

निम्नलिखित नमूना कोड दिखाता है कि PowerPoint प्रस्तुति में ग्रिड स्पेसिंग को कैसे बदलें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [IViewProperties](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)