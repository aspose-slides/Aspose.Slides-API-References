---
title: AreEqual()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: AreEqual असर्शन अनुवाद के लिए तर्कों की समान-तुलना करता है।
type: docs
weight: 14
url: /hi/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) फ़ंक्शन

Equal-तुलना करता है तर्कों की AreEqual असर्शन अनुवाद के लिए।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1\&& | LHS मान। |
| rhs | T2\&& | RHS मान। |

### रिटर्न वैल्यू

gtest-शैली वाला असर्शन परिणाम।

## संबंधित देखें

* नामस्थान [System::TestPredicates](../)
* लाइब्रेरी [Aspose.Slides](../../)