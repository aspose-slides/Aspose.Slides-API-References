---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API संदर्भ
description: yield फ़ंक्शन से एक IEnumerable बनाता है।
type: docs
weight: 2419
url: /hi/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) फ़ंक्शन

Creates an IEnumerable from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | क्रम में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | निष्पादित करने के लिए yield फ़ंक्शन |

### वापसी मान

IEnumerable के लिए समान पॉइंटर

## संबंधित देखें

* Typedef [SharedPtr](../sharedptr/)
* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)