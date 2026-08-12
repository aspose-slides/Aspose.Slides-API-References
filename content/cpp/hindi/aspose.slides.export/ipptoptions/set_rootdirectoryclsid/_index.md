---
title: set_RootDirectoryClsid()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: रूट डायरेक्टरी एंट्री में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) का प्रतिनिधित्व करता है। इसे दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।
type: docs
weight: 14
url: /hi/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) मेथड

रूट डायरेक्टरी एंट्री में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) का प्रतिनिधित्व करता है। इसे दस्तावेज़ के एप्लिकेशन की COM सक्रियता के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मान '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से मेल खाता है।

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* क्लास [IPptOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)