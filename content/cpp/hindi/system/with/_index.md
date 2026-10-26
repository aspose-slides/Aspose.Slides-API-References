---
title: With()
second_title: Aspose.Slides for C++ API संदर्भ
description: संदर्भ रिकॉर्ड की क्लोन बनाता है और उस पर इनिशियलाइज़र फ़ंक्टर लागू करता है।
type: docs
weight: 2614
url: /hi/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) फ़ंक्शन

रेफ़रेंस रिकॉर्ड की क्लोन बनाता है और उस पर इनिशियलाइज़र फ़ंक्टर लागू करता है।

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | क्लोन करने के लिए रिकॉर्ड प्रकार। |
| A | इनिशियलाइज़र फ़ंक्टर का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | क्लोन और इनिशियलाइज़ करने वाले ऑब्जेक्ट का शेयर्ड पॉइंटर। |
| initializer | const A\& | रिकॉर्ड क्लोन पर लागू किया जाने वाला इनिशियलाइज़र फ़ंक्टर। |

### वापसी मान

क्लोन किए गए रिकॉर्ड का शेयर्ड पॉइंटर।

## System::With(const T\&, const A\&) फ़ंक्शन

संरचना रिकॉर्ड की कॉपी बनाता है और उस पर इनिशियलाइज़र फ़ंक्टर लागू करता है।

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कॉपी करने के लिए रिकॉर्ड प्रकार। |
| A | इनिशियलाइज़र फ़ंक्टर का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| record | const T\& | कॉपी और इनिशियलाइज़ करने वाला रिकॉर्ड। |
| initializer | const A\& | रिकॉर्ड कॉपी पर लागू किया जाने वाला इनिशियलाइज़र फ़ंक्टर। |

### वापसी मान

कॉपी किया गया रिकॉर्ड।

## संबंधित देखें

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)