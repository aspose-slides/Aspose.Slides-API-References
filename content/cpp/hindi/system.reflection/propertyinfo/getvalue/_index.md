---
title: GetValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: विशिष्ट ऑब्जेक्ट से प्रॉपर्टी मान प्राप्त करता है।
type: docs
weight: 1
url: /hi/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) विधि

विशिष्ट ऑब्जेक्ट से प्रॉपर्टी मान प्राप्त करता है।

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) से प्रॉपर्टी पढ़ने के लिए। |

### रिटर्न वैल्यू

निर्दिष्ट ऑब्जेक्ट के लिए निर्दिष्ट प्रॉपर्टी का मान।

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) विधि

विशिष्ट ऑब्जेक्ट से प्रॉपर्टी मान प्राप्त करता है।

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) से प्रॉपर्टी पढ़ने के लिए। |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | ये अनुक्रमित प्रॉपर्टी के लिए वैकल्पिक इंडेक्स मान हैं। गैर-अनुक्रमित प्रॉपर्टी के लिए, इस मान का मान null होना चाहिए। |

### रिटर्न वैल्यू

निर्दिष्ट ऑब्जेक्ट के लिए निर्दिष्ट प्रॉपर्टी का मान।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Object](../../../system/object/)
* क्लास [PropertyInfo](../)
* नेमस्पेस [System::Reflection](../../)
* लाइब्रेरी [Aspose.Slides](../../../)