---
title: Cast()
second_title: Aspose.Slides for C++ API संदर्भ
description: SmartPtr ऑब्जेक्ट्स पर कास्ट करता है।
type: docs
weight: 2510
url: /hi/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) फ़ंक्शन


[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर कास्ट करता है।

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्ष्य पॉइंटी टाइप। |
| TFrom | स्रोत पॉइंटी टाइप। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | स्रोत पॉइंटर। |

### वापसी मान

यदि कास्ट की अनुमति है तो कास्ट परिणाम।

## संबंधित

* वर्ग [SmartPtr](../smartptr/)
* संरचना [IsExceptionWrapper](../isexceptionwrapper/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)