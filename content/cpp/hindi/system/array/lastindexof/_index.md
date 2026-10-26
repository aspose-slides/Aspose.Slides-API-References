---
title: LastIndexOf()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि निर्दिष्ट आइटम की अंतिम उपस्थिति का सूचकांक क्या है, जो ऐरे के उन आइटमों की रेंज में है जिसे प्रारंभ सूचकांक और रेंज में तत्वों की संख्या द्वारा निर्दिष्ट किया गया है।
type: docs
weight: 703
url: /hi/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) विधि

निर्दिष्ट आइटम की अंतिम उपस्थिति का इंडेक्स निर्धारित करता है, जो ऐरे के उन आइटमों की रेंज में है जिसे प्रारंभ इंडेक्स और रेंज में तत्वों की संख्या द्वारा निर्दिष्ट किया गया है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम को खोजने के लिए |
| value | const [ValueType](../valuetype/)\& | जिस आइटम का इंडेक्स निर्धारित किया जाना है |
| startIndex | int | [Index](../../index/) जिस बिंदु पर खोज शुरू की जाती है |
| count | int | रेंज में खोजे जाने वाले तत्वों की संख्या |

### वापसी मान

[Index](../../index/) यदि आइटम पाया जाता है तो निर्दिष्ट आइटम की अंतिम उपस्थिति का, अन्यथा -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) विधि

निर्दिष्ट इंडेक्स से शुरू होकर ऐरे में निर्दिष्ट आइटम की अंतिम उपस्थिति का इंडेक्स निर्धारित करता है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम को खोजने के लिए |
| value | const [ValueType](../valuetype/)\& | जिस आइटम का इंडेक्स निर्धारित किया जाना है |
| startIndex | int | [Index](../../index/) जिस बिंदु पर खोज शुरू की जाती है |

### वापसी मान

[Index](../../index/) यदि आइटम पाया जाता है तो निर्दिष्ट आइटम की अंतिम उपस्थिति का, अन्यथा -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) विधि

ऐरे में निर्दिष्ट आइटम की अंतिम उपस्थिति का इंडेक्स निर्धारित करता है।

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ArrayType | लक्ष्य ऐरे में तत्वों का प्रकार |
| ValueType | ऐरे में खोजे जाने वाले आइटम का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) निर्दिष्ट आइटम को खोजने के लिए |
| value | const [ValueType](../valuetype/)\& | जिस आइटम का इंडेक्स निर्धारित किया जाना है |

### वापसी मान

[Index](../../index/) यदि आइटम पाया जाता है तो निर्दिष्ट आइटम की अंतिम उपस्थिति का, अन्यथा -1

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* वर्ग [Array](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)