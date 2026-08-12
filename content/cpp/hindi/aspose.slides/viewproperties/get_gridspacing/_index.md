---
title: get_GridSpacing()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेज़ेंटेशन दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट्स में लौटाता है। Read float.
type: docs
weight: 92
url: /hi/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() विधि

Returns the grid spacing that should be used for the grid underlying the presentation document, in points. Read **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## टिप्पणियाँ

The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points). 

The following sample code shows how to change the grid spacing in a PowerPoint presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## देखें भी

* Class [ViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)