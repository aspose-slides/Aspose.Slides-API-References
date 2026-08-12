---
title: UnknownIsNull()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जाँचता है कि अज्ञात प्रकार का ऑब्जेक्ट nullptr है या नहीं। गैर-स्केलर प्रकारों के लिए ओवरलोड।
type: docs
weight: 144
url: /hi/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) मेथड

जाँचता है कि अज्ञात प्रकार का ऑब्जेक्ट nullptr है या नहीं। गैर-स्केलर प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) प्रकार. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T | [Object](../../object/) जाँचने के लिए। |

### रिटर्न वैल्यू

यदि 'obj == nullptr' सत्य है तो true, अन्यथा false।

## ObjectExt::UnknownIsNull(T) मेथड

जाँचता है कि अज्ञात प्रकार का ऑब्जेक्ट nullptr है या नहीं। स्केलर प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) प्रकार. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T | [Object](../../object/) जाँचने के लिए। |

### रिटर्न वैल्यू

हमेशा false लौटाता है।

## देखें

* क्लास [ObjectExt](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)