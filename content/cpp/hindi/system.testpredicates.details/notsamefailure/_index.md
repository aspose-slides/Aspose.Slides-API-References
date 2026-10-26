---
title: NotSameFailure()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: आउटपुट के लिए 'not same' आश्वासन विफलता को स्वरूपित करता है।
type: docs
weight: 66
url: /hi/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) फ़ंक्शन

आउटपुट के लिए 'not same' आश्वासन विफलता को स्वरूपित करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS मान प्रकार। |
| T2 | RHS मान प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1\& | LHS मान। |
| rhs | T2\& | RHS मान। |

### रिटर्न मान

[Object](../../system/object/) विफलता पाठ को लपेटना।

## संबंधित देखें

* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)