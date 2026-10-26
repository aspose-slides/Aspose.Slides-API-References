---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।
type: docs
weight: 79
url: /hi/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) मेथड

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एम्बेडेड OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### रिटर्न वैल्यू

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) मेथड

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | [System::String](../../../system/string/) | OLE वस्तु का क्लास नाम। |
| path | [System::String](../../../system/string/) | लिंक्ड फ़ाइल का पथ। |

### रिटर्न वैल्यू

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## टिप्पणी

यह पथ प्रस्तुति में जैसे का तैसा संग्रहीत किया जाता है। यदि एक सापेक्ष पथ निर्दिष्ट किया गया है, तो अलग निर्देशिका से प्रस्तुति खोलने पर फ़ाइल पहुंच योग्य नहीं होगी।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOleObjectFrame](../../ioleobjectframe/)
* क्लास [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* क्लास [IShapeCollection](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)