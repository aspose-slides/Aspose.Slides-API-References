---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API संदर्भ
description: अक्षर आगे की खोज।
type: docs
weight: 638
url: /hi/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const विधि

अक्षर आगे की खोज।

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | char_t | खोजने के लिए अक्षर। |
| startIndex | int | [Index](../../index/) खोज शुरू करने का इंडेक्स। |

### वापसी मान

[Index](../../index/) पहला अक्षर स्थिति, startIndex से, या नहीं मिला तो -1।

## String::IndexOfAny(const String\&, int) const विधि

इसमें str के सभी अक्षरों को क्रमशः खोजता है। यदि पहला अक्षर मिला, उसका स्थान लौटाता है, अन्यथा दूसरा अक्षर खोजता है और इसी प्रकार आगे।

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) खोजने के लिए अक्षरों का समूह। अक्षरों का क्रम महत्व रखता है। |
| startIndex | int | खोज शुरू करने का स्थान। |

### वापसी मान

[Index](../../index/) पहला मिला अक्षर का इंडेक्स या -1 यदि नहीं मिला।

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const विधि

पूरे स्ट्रिंग में पास किए गए किसी भी अक्षर को खोजता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा और इसी प्रकार आगे। लक्ष्य अक्षरों में से किसी से मेल खाने वाले पहले अक्षर का इंडेक्स लौटाता है।

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजने के लिए अक्षरों का समूह। क्रम का महत्व नहीं है। |

### वापसी मान

[Index](../../index/) पहला मेल खाने वाला अक्षर का इंडेक्स या -1 यदि नहीं मिला।

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const विधि

पूरा स्ट्रिंग के उपस्ट्रिंग में पास किए गए किसी भी अक्षर को खोजता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा और इसी प्रकार आगे। लक्ष्य अक्षरों में से किसी से मेल खाने वाले पहले अक्षर का इंडेक्स लौटाता है।

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजने के लिए अक्षरों का समूह। क्रम का महत्व नहीं है। |
| startindex | **int32_t** | [Index](../../index/) खोज शुरू करने का इंडेक्स। |

### वापसी मान

[Index](../../index/) पहला मेल खाने वाला अक्षर का इंडेक्स या -1 यदि नहीं मिला।

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const विधि

पूरा स्ट्रिंग के उपस्ट्रिंग में पास किए गए किसी भी अक्षर को खोजता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा और इसी प्रकार आगे। लक्ष्य अक्षरों में से किसी से मेल खाने वाले पहले अक्षर का इंडेक्स लौटाता है।

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) खोजने के लिए अक्षरों का समूह। क्रम का महत्व नहीं है। |
| startindex | **int32_t** | [Index](../../index/) खोज शुरू करने का इंडेक्स। |
| count | **int32_t** | देखे जाने वाले अक्षरों की संख्या। |

### वापसी मान

[Index](../../index/) पहला मेल खाने वाला अक्षर का इंडेक्स या -1 यदि नहीं मिला।

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)