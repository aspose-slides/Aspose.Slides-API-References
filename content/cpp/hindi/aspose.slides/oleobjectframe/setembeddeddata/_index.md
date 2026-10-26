---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API संदर्भ
description: OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।
type: docs
weight: 248
url: /hi/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) विधि

OLE एम्बेडेड डेटा के बारे में सूचना सेट करता है।

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एंबेडेड डेटा [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## टिप्पणी

यह विधि ऑब्जेक्ट की प्रॉपर्टी को बदलता है ताकि नई डेटा को प्रतिबिंबित किया जा सके और IsObjectLink फ़्लैग को false सेट करता है, यह संकेत देते हुए कि OLE ऑब्जेक्ट एम्बेडेड है। 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## अन्य देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* क्लास [OleObjectFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)