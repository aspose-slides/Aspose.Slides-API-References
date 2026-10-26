---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API संदर्भ
description: Object को अज्ञात प्रकार में परिवर्तित करता है, दोनों स्मार्ट पॉइंटर प्रकार और bpxed वैल्यू स्थितियों को संभालते हुए।
type: docs
weight: 131
url: /hi/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) मेथड

[Object](../../object/) को अज्ञात प्रकार में परिवर्तित करता है, दोनों स्मार्ट पॉइंटर प्रकार और bpxed वैल्यू स्थितियों को संभालते हुए।

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) को परिवर्तित करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) को परिवर्तित करने के लिए। |

### रिटर्न वैल्यू

या तो अनबॉक्स्ड वैल्यू या परिवर्तित पॉइंटर।

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) मेथड

[Object](../../object/) को अज्ञात प्रकार में परिवर्तित करता है, दोनों स्मार्ट पॉइंटर प्रकार और बॉक्स्ड वैल्यू स्थितियों को संभालते हुए।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../object/) को परिवर्तित करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) को परिवर्तित करने के लिए। |

### रिटर्न वैल्यू

या तो अनबॉक्स्ड वैल्यू या परिवर्तित पॉइंटर।

## संबंधित देखें

* क्लास [SmartPtr](../../smartptr/)
* क्लास [Object](../../object/)
* क्लास [ObjectExt](../)
* स्ट्रक्ट [IsSmartPtr](../../issmartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)