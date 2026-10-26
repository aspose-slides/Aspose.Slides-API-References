---
title: InitObject()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: शेयर किए गए स्वामित्व के साथ एक ऑब्जेक्ट की प्रारंभिककरण शुरू करता है।
type: docs
weight: 2263
url: /hi/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) फ़ंक्शन

एक ऑब्जेक्ट को साझा स्वामित्व के साथ प्रारम्भ करता है।

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रारम्भ करने के लिए ऑब्जेक्ट का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) को प्रारम्भ करने के लिए |

### वापसी मान

ObjectBuilder को साझा पॉइंटर निर्माण के लिए कॉन्फ़िगर किया गया

## टिप्पणियाँ

[Object](../object/) इनिशियलाइज़ेशन को [Get()](../get/) कॉल के साथ समाप्त किया जाना चाहिए

## संबंधित

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* लाइब्रेरी [Aspose.Slides](../../)