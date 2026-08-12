---
title: Trim()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग की शुरुआत और अंत दोनों से सभी whitespace अक्षरों को हटाता है।
type: docs
weight: 677
url: /hi/system/string/trim/
---
## String::Trim() const विधि

शुरुआत और अंत दोनों से सभी whitespace अक्षरों को हटा देता है।

```cpp
String System::String::Trim() const
```

### Return Value

[String](../) में शुरुआत या अंत में कोई whitespace नहीं।

## String::Trim(char_t) const विधि

शुरुआत और अंत दोनों से पास किए गए अक्षर की सभी आवृत्तियों को हटा देता है।

```cpp
String System::String::Trim(char_t ch) const
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ch | char_t | हटाने के लिए प्रतीक। |

### Return Value

हटाने का परिणाम।

## String::Trim(const String\&) const विधि

शुरुआत और अंत दोनों से Passed characters की सभी occurrences को हटा देता है।

```cpp
String System::String::Trim(const String &anyOf) const
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) हटाने के लिए अक्षरों का। |

### Return Value

[String](../) हटाए गए अक्षरों के बिना।

## String::Trim(const ArrayPtr\<char_t\>\&) const विधि

शुरुआत और अंत दोनों से Passed characters की सभी occurrences को हटा देता है।

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) हटाने के लिए अक्षरों का। |

### Return Value

[String](../) हटाए गए अक्षरों के बिना।

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)