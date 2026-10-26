---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि प्रस्तुति लोड होने के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।
type: docs
weight: 339
url: /hi/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() मेथड

[Aspose.Slides](../../) प्रस्तुति लोड होने के समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं, यह निर्धारित करता है।

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## टिप्पणियाँ

एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) बाइनरी डेटा [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

पढ़ें **bool**.

डिफ़ॉल्ट **false** है।

निम्न उदाहरण दिखाता है कि प्रस्तुति को बिना किसी एम्बेडेड बाइनरी ऑब्जेक्ट के कैसे लोड किया जाए।
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## संबंधित देखें

* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)