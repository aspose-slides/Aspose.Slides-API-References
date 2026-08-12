---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि प्रस्तुति लोड करते समय Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।
type: docs
weight: 339
url: /hi/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() विधि


निर्धारित करता है कि [Aspose.Slides](../../) प्रस्तुति लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटा देगा या नहीं।

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## टिप्पणी


एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

* VBA प्रोजेक्ट [IPresentation::VbaProject](../)
* OLE ऑब्जेक्ट एम्बेडेड डेटा [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) बाइनरी डेटा [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


पढ़ें **bool**। 

डिफ़ॉल्ट **false** है। 

निम्न उदाहरण दर्शाता है कि प्रस्तुति को बिना किसी एम्बेडेड बाइनरी ऑब्जेक्ट के कैसे लोड किया जाए। 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## देखें

* क्लास [ILoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)