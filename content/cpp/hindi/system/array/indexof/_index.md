---
title: IndexOf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि सरणी में निर्दिष्ट आइटम की पहली उपस्थिति का सूचकांक क्या है।
type: docs
weight: 131
url: /hi/system/array/indexof/
---
## Array::IndexOf(const T\&) const method

ऐरे में निर्दिष्ट आइटम की पहली घटना का सूचकांक निर्धारित करता है।

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | const T\& | जिसका सूचकांक निर्धारित किया जाना है |

### रिटर्न वैल्यू

[Index](../../index/) यदि आइटम मिला तो निर्दिष्ट आइटम की पहली घटना का, अन्यथा -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method

ऐरे में निर्दिष्ट आइटम की पहली घटना का सूचकांक निर्धारित करता है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम की खोज के लिए |
| value | const [ValueType](../valuetype/)\& | जिसका सूचकांक निर्धारित किया जाना है |

### रिटर्न वैल्यू

[Index](../../index/) यदि आइटम मिला तो निर्दिष्ट आइटम की पहली घटना का, अन्यथा -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method

निर्दिष्ट सूचकांक से शुरू करके, ऐरे में निर्दिष्ट आइटम की पहली घटना का सूचकांक निर्धारित करता है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम की खोज के लिए |
| value | const [ValueType](../valuetype/)\& | जिसका सूचकांक निर्धारित किया जाना है |
| startIndex | int | [Index](../../index/) जहाँ खोज शुरू की जाती है |

### रिटर्न वैल्यू

[Index](../../index/) यदि आइटम मिला तो निर्दिष्ट आइटम की पहली घटना का, अन्यथा -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method

स्टार्ट इंडेक्स और रेंज में तत्वों की संख्या द्वारा निर्दिष्ट रेंज में, ऐरे के आइटमों की रेंज में निर्दिष्ट आइटम की पहली घटना का सूचकांक निर्धारित करता है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम की खोज के लिए |
| value | const [ValueType](../valuetype/)\& | जिसका सूचकांक निर्धारित किया जाना है |
| startIndex | int | [Index](../../index/) जहाँ खोज शुरू की जाती है |
| count | int | रेंज में खोजे जाने वाले तत्वों की संख्या |

### रिटर्न वैल्यू

[Index](../../index/) यदि आइटम मिला तो निर्दिष्ट आइटम की पहली घटना का, अन्यथा -1

## देखें भी

* टाइपडिफ़ [ArrayPtr](../../arrayptr/)
* टाइपडिफ़ [ValueType](../valuetype/)
* क्लास [Array](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)