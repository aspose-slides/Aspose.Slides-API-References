---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API संदर्भ
description: Is-instance-of-तर्कों की तुलना करता है IsInstanceOf सत्यापन अनुवाद के लिए।
type: docs
weight: 118
url: /hi/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) फ़ंक्शन

Is-instance-of-तर्कों की तुलना करता है IsInstanceOf सत्यापन अनुवाद के लिए।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | Argument type. |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | A typeInfo object that represents a type against which the type of **obj** is to be compared |
| obj | const T\& | An object whose type to compare with the specified type |

### रिटर्न वैल्यू

gtest-styled assertion result.

## देखें

* क्लास [TypeInfo](../../system/typeinfo/)
* नेमस्पेस [System::TestPredicates](../)
* लाइब्रेरी [Aspose.Slides](../../)