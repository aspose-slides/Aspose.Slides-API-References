---
title: ConstCast()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिप्रिकेटेड कास्टस का अंत।
type: docs
weight: 2575
url: /hi/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) फ़ंक्शन


डिप्रिकेटेड कास्टस का अंत।

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TTo | लक्षित पॉइनी प्रकार। |
| TFrom | स्रोत पॉइनी प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | स्रोत पोइंटर। |

### रिटर्न वैल्यू

यदि कास्ट की अनुमति है तो कास्ट परिणाम, अन्यथा nullptr।

## टिप्पणियाँ

[SmartPtr](../smartptr/) ऑब्जेक्ट्स पर const कास्ट करता है।

## देखें

* क्लास [SmartPtr](../smartptr/)
* स्ट्रक्चर [CastResult](../castresult/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)