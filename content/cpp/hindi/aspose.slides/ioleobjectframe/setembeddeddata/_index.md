---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API संदर्भ
description: OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।
type: docs
weight: 248
url: /hi/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) मेथड

OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एम्बेडेड डेटा [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## टिप्पणियाँ

यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा को प्रतिबिंबित करने के लिए बदलता है और IsObjectLink फ़्लैग को false सेट करता है, यह संकेत देते हुए कि OLE ऑब्जेक्ट एम्बेडेड है।

निम्न उदाहरण दर्शाता है कि मौजूदा [IOleObjectFrame](../) ऑब्जेक्ट के लिए OLE एम्बेडेड डेटा और उसके प्रकार को कैसे बदलें
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## संबंधित देखें

* टाइपडैफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* क्लास [IOleObjectFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)