---
title: UnknownToObject()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अज्ञात प्रकार को Object में परिवर्तित करता है, स्मार्ट पॉइंटर प्रकार और वैल्यू प्रकार दोनों स्थितियों को संभालता है।
type: docs
weight: 118
url: /hi/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) विधि

अज्ञात प्रकार को [Object](../../object/) में परिवर्तित करता है, स्मार्ट पॉइंटर प्रकार और वैल्यू प्रकार दोनों स्थितियों को संभालता है।

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) में परिवर्तित करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | T | [Object](../../object/) को परिवर्तित करने के लिए। |

### रिटर्न मान

[Object](../../object/) के लिए स्मार्ट पॉइंटर, जो या तो परिवर्तित पॉइंटर या बॉक्स्ड वैल्यू है।

## ObjectExt::UnknownToObject(const T\&) विधि

अज्ञात प्रकार को [Object](../../object/) में परिवर्तित करता है, स्मार्ट पॉइंटर प्रकार और वैल्यू प्रकार दोनों स्थितियों को संभालता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) में परिवर्तित करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) को परिवर्तित करने के लिए। |

### रिटर्न मान

[Object](../../object/) के लिए स्मार्ट पॉइंटर, जो या तो परिवर्तित पॉइंटर या बॉक्स्ड वैल्यू है।

## संबंधित देखें

* क्लास [SmartPtr](../../smartptr/)
* क्लास [Object](../../object/)
* क्लास [ObjectExt](../)
* स्ट्रक्चर [IsSmartPtr](../../issmartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)