---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया उदाहरण बनाता है।
type: docs
weight: 14
url: /hi/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) कन्स्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | एक असिंक्रोनस ऑपरेशन के दौरान हुई कोई भी त्रुटि। |
| cancelled | **bool** | एक मान जो दर्शाता है कि असिंक्रोनस ऑपरेशन रद्द किया गया है या नहीं। |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | वैकल्पिक उपयोगकर्ता-द्वारा प्रदान किया गया स्थिति ऑब्जेक्ट जो [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) मेथड को पास किया जाता है। |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | एक संग्रह जिसमें असिंक्रोनस ऑपरेशन के परिणाम होते हैं। |

## देखें

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Object](../../../system/object/)
* क्लास [InvokeCompletedEventArgs](../)
* नामस्थान [System::Web::Services::Protocols](../../)
* लाइब्रेरी [Aspose.Slides](../../../)