---
title: TrimEnd()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग के अंत से सभी व्हाइटस्पेस अक्षर हटाता है।
type: docs
weight: 703
url: /hi/system/string/trimend/
---
## String::TrimEnd() const विधि


स्ट्रिंग के अंत से सभी व्हाइटस्पेस अक्षर हटाता है।

```cpp
String System::String::TrimEnd() const
```


### रिटर्न वैल्यू

[String](../) के साथ शुरू में कोई व्हाइटस्पेस नहीं।

## String::TrimEnd(char_t) const विधि


स्ट्रिंग के अंत से पास किए गए अक्षर की सभी घटनाएँ हटाता है।

```cpp
String System::String::TrimEnd(char_t ch) const
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ch | char_t | हटाने के लिए संकेत। |

### रिटर्न वैल्यू

हटाने का परिणाम।

## String::TrimEnd(const String\&) const विधि


स्ट्रिंग के अंत से पास किए गए वर्णों की सभी घटनाएँ हटाता है।

```cpp
String System::String::TrimEnd(const String &anyOf) const
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [String](../)\& | हटाने के लिए वर्णों का [String](../)। |

### रिटर्न वैल्यू

[String](../) बिना हटाए गए वर्णों के।

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const विधि


स्ट्रिंग के अंत से पास किए गए वर्णों की सभी घटनाएँ हटाता है।

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | हटाने के लिए वर्णों का [Array](../../array/)। |

### रिटर्न वैल्यू

[String](../) बिना हटाए गए वर्णों के।

## देखें भी

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)