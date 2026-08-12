---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शैप कलेक्शन के अंत में जोड़ता है।
type: docs
weight: 183
url: /hi/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) विधि

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शैप कलेक्शन के अंत में जोड़ता है।

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एम्बेडेड OLE डेटा के बारे में जानकारी ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/))। |

### वापसी मान

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## टिप्पणी

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint [Presentation](../../presentation/) के [Slides](../../) में OLE ऑब्जेक्ट फ्रेम कैसे जोड़ें। 
```cpp
auto pres = System::MakeObject<Presentation>();

// पहली स्लाइड तक पहुँचता है
auto slide = pres->get_Slides()->idx_get(0);
// एक्सेल फ़ाइल को स्ट्रीम में लोड करता है
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// एम्‍बेडिंग के लिए डेटा ऑब्जेक्ट बनाता है
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Ole ऑब्जेक्ट फ्रेम शेप जोड़ता है
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//PPTX फ़ाइल को डिस्क पर लिखता है
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) विधि

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शैप कलेक्शन के अंत में जोड़ता है।

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | [System::String](../../../system/string/) | OLE ऑब्जेक्ट का क्लास नाम। |
| path | [System::String](../../../system/string/) | लिंक्ड फ़ाइल का पथ। |

### वापसी मान

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## टिप्पणी

यह पथ प्रस्तुति में जैसा है वैसा ही संग्रहीत रहता है। यदि एक सापेक्ष पथ निर्दिष्ट किया जाता है, तो प्रस्तुति को किसी अलग निर्देशिका से खोलने पर फ़ाइल पहुंच योग्य नहीं होगी।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)