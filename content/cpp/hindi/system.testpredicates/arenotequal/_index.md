---
title: AreNotEqual()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: असमान तर्कों की तुलना AreEqual असर्शन अनुवाद के लिए करता है।
type: docs
weight: 40
url: /hi/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) function


Not-equal तर्कों की तुलना AreEqual असर्शन अनुवाद के लिए करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1\&& | LHS मान। |
| rhs | T2\&& | RHS मान। |

### रिटर्न वैल्यू

gtest-शैली का असर्शन परिणाम।

## संबंधित देखें

* नेमस्पेस [System::TestPredicates](../)
* लाइब्रेरी [Aspose.Slides](../../)