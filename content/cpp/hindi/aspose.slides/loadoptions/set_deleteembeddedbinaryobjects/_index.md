---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि प्रस्तुति लोडिंग के दौरान Aspose.Slides सभी एंबेडेड बाइनरी वस्तुओं को हटाएगा या नहीं।
type: docs
weight: 352
url: /hi/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) विधि


निर्धारित करता है कि [Aspose.Slides](../../) प्रस्तुति लोड करते समय सभी एंबेडेड बाइनरी वस्तुओं को हटा देगा या नहीं।

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## टिप्पणियाँ


एंबेडेड बाइनरी वस्तुओं के प्रकार:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) बाइनरी डेटा [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


लिखें **bool**. 

डिफ़ॉल्ट **false** है। 

निम्नलिखित उदाहरण दिखाता है कि एंबेडेड बाइनरी वस्तुओं के बिना प्रस्तुति को कैसे लोड किया जाए। 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## संबंधित देखें

* क्लास [LoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)