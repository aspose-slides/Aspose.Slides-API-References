---
title: Cast_noexcept()
second_title: Aspose.Slides for C++ API संदर्भ
description: SmartPtr ऑब्जेक्ट्स पर कास्ट करता है।
type: docs
weight: 2497
url: /hi/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) फ़ंक्शन


[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइनी टाइप। |
| TFrom | स्रोत पॉइनी टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### रिटर्न वैल्यू

यदि कास्ट अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

## संबंधित देखें

* क्लास [SmartPtr](../smartptr/)
* स्ट्रक्ट [IsExceptionWrapper](../isexceptionwrapper/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)