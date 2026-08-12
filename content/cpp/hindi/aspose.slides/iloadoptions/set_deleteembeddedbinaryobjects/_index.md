---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि प्रस्तुति लोड करते समय Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।
type: docs
weight: 352
url: /hi/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) मेथड


निर्धारित करता है कि [Aspose.Slides](../../) प्रस्तुति लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## टिप्पणी


एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


लिखें **bool**। 

डिफ़ॉल्ट **false** है। 

निम्नलिखित उदाहरण दिखाता है कि कैसे प्रस्तुति को बिना किसी एम्बेडेड बाइनरी ऑब्जेक्ट के लोड किया जाए। 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## देखें

* क्लास [ILoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)