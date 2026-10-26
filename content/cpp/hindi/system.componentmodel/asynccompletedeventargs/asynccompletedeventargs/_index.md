---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्माता।
type: docs
weight: 1
url: /hi/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() निर्माता

निर्माता।

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) निर्माता

नया उदाहरण प्रारंभ करता है [System.ComponentModel.AsyncCompletedEventArgs](../) क्लास का।

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | ऐसी कोई भी त्रुटि जो असिंक्रोनस संचालन के दौरान हुई। |
| canceled | **bool** | एक मान जो दर्शाता है कि असिंक्रोनस संचालन रद्द किया गया था या नहीं। |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | वैकल्पिक उपयोगकर्ता-प्रदान किया गया स्थिति वस्तु जो [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) विधि को पास किया जाता है। |

## देखें भी

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [AsyncCompletedEventArgs](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [System::ComponentModel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)