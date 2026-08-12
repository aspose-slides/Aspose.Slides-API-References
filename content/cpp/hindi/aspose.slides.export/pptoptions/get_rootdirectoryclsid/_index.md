---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रूट डायरेक्टरी प्रविष्टि में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) का प्रतिनिधित्व करता है। दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' के अनुरूप है।
type: docs
weight: 1
url: /hi/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() विधि


रूट डायरेक्टरी प्रविष्टि में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) का प्रतिनिधित्व करता है। दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' के अनुरूप है।

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## देखें

* क्लास [Guid](../../../system/guid/)
* क्लास [PptOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)