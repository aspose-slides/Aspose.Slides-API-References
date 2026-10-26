---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।
type: docs
weight: 196
url: /hi/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में सम्मिलित करता है।

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एम्बेडेड OLE डेटा सूचना ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/))। |

### रिटर्न मान

नव निर्मित [IOleObjectFrame](../../ioleobjectframe/)।

## टिप्पणी

यह उदाहरण दूसरे इंडेक्स पर OLE ऑब्जेक्ट डालने को दर्शाता है: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में सम्मिलित करता है।

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने के लिए शून्य-आधारित सूचकांक। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | [System::String](../../../system/string/) | OLE ऑब्जेक्ट का क्लास नाम। |
| path | [System::String](../../../system/string/) | लिंक की गई फ़ाइल का पथ। |

### रिटर्न मान

नव निर्मित OLE ऑब्जेक्ट फ्रेम।

## टिप्पणी

यह पथ प्रस्तुति में जैसा है वैसा ही संग्रहीत रहता है। यदि कोई सापेक्ष पथ निर्दिष्ट किया गया है, तो अलग डायरेक्टरी से प्रस्तुति खोलते समय फ़ाइल अनुपलब्ध होगी।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOleObjectFrame](../../ioleobjectframe/)
* क्लास [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* क्लास [ShapeCollection](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)