---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।
type: docs
weight: 66
url: /hi/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) मेथड

नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए OLE फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊंचाई, पॉइंट्स में। |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | एम्बेडेड OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/))। |

### रिटर्न वैल्यू

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) मेथड

नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए OLE फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊंचाई, पॉइंट्स में। |
| className | [System::String](../../../system/string/) | OLE ऑब्जेक्ट का क्लास नाम। |
| path | [System::String](../../../system/string/) | लिंक की गई फ़ाइल का पाथ। |

### रिटर्न वैल्यू

नया बनाया गया [IOleObjectFrame](../../ioleobjectframe/)।

## टिप्पणी

यह पाथ प्रस्तुति में जैसा है वैसा ही संग्रहीत किया जाता है। यदि सापेक्ष पाथ निर्दिष्ट किया जाता है, तो किसी अलग डायरेक्टरी से प्रस्तुति खोलने पर फ़ाइल तक पहुंच संभव नहीं होगी।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)