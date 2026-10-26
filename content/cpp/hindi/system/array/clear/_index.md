---
title: Clear()
second_title: Aspose.Slides for C++ API संदर्भ
description: समर्थित नहीं है क्योंकि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया एरे केवल-रीड है।
type: docs
weight: 53
url: /hi/system/array/clear/
---
## Array::Clear() मेथड

समर्थित नहीं है क्योंकि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया एरे केवल-रीड है।

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) मेथड

निर्दिष्ट एरे में **startIndex** इंडेक्स से शुरू होकर **count** मानों को डिफ़ॉल्ट मानों से प्रतिस्थापित करता है।

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Type | target array में तत्वों का Type |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | लक्षित एरे |
| startIndex | int | [Index](../../index/) जिस इंडेक्स पर आइटम बदलना शुरू किया जाता है |
| count | int | बदलने के लिए आइटम की संख्या |

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)