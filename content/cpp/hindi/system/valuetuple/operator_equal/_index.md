---
title: operator=()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 92
url: /hi/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) विधि




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) विधि


ऑब्जेक्ट को इस वैल्यू ट्यूपल में विघटित करता है।

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | विघटित करने के लिये एक ऑब्जेक्ट |

## देखें

* टाइपडेफ़ [SharedPtr](../../sharedptr/)
* क्लास [ValueTuple](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)