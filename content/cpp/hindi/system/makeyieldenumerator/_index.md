---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक yield फ़ंक्शन से IEnumerator बनाता है।
type: docs
weight: 2432
url: /hi/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) फ़ंक्शन

एक yield फ़ंक्शन से IEnumerator बनाता है।

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | क्रम में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | चलाने के लिए yield फ़ंक्शन |

### वापसी मान

IEnumerator के लिए शेयर किया गया पॉइंटर

## संबंधित

* टाइपडिफ़ [SharedPtr](../sharedptr/)
* क्लास [IEnumerator](../../system.collections.generic/ienumerator/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)