---
title: SetValue()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: विशिष्ट ऑब्जेक्ट के लिए प्रॉपर्टी मान सेट करता है।
type: docs
weight: 14
url: /hi/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) विधि

विशिष्ट ऑब्जेक्ट के लिए प्रॉपर्टी मान सेट करता है।

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) प्रॉपर्टी लिखने के लिए |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | सेट करने के लिए प्रॉपर्टी का मान |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) विधि

विशिष्ट ऑब्जेक्ट के लिए प्रॉपर्टी मान सेट करता है।

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) प्रॉपर्टी लिखने के लिए |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ये अनुक्रमित प्रॉपर्टीज़ के वैकल्पिक इंडेक्स मान हैं। गैर-अनुक्रमित प्रॉपर्टीज़ के लिए, यह मान null होना चाहिए। |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | सेट करने के लिए प्रॉपर्टी का मान |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)