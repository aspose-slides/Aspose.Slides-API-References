---
title: IndexOf()
second_title: Aspose.Slides for C++ API संदर्भ
description: सबस्ट्रिंग आगे की खोज।
type: docs
weight: 625
url: /hi/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method

सबस्ट्रिंग आगे की खोज।

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | खोज के लिए सबस्ट्रिंग। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### रिटर्न वैल्यू

[Index](../../index/) पहला पाया गया सबस्ट्रिंग का या -1 यदि नहीं मिला। खाली लुकअप स्ट्रिंग के लिए, हमेशा 0 लौटाता है।

## String::IndexOf(char_t, int) const method

अक्षर आगे की खोज।

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | char_t | खोज के लिए अक्षर। |
| startIndex | int | [Index](../../index/) पर लुकअप शुरू करने के लिए। |

### रिटर्न वैल्यू

[Index](../../index/) startIndex के बाद पहला अक्षर स्थिती या -1 यदि नहीं मिला।

## String::IndexOf(char_t, int, int) const method

सबस्ट्रिंग में अक्षर आगे की खोज।

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | char_t | खोज के लिए अक्षर। |
| startIndex | int | [Index](../../index/) पर लुकअप शुरू करने के लिए। |
| count | int | देखने के लिए अक्षरों की संख्या। |

### रिटर्न वैल्यू

[Index](../../index/) startIndex के बाद पहला अक्षर स्थिती या -1 यदि नहीं मिला।

## String::IndexOf(const String\&, int) const method

सबस्ट्रिंग आगे की खोज।

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | खोज के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में लुकअप शुरू करने की स्थिति। |

### रिटर्न वैल्यू

[Index](../../index/) पहला पाया गया सबस्ट्रिंग का या -1 यदि नहीं मिला। खाली लुकअप स्ट्रिंग के लिए, हमेशा startIndex लौटाता है।

## String::IndexOf(const String\&, int, System::StringComparison) const method

सबस्ट्रिंग आगे की खोज।

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | खोज के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में लुकअप शुरू करने की स्थिति। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### रिटर्न वैल्यू

[Index](../../index/) पहला पाया गया सबस्ट्रिंग का या -1 यदि नहीं मिला। खाली लुकअप स्ट्रिंग के लिए, हमेशा startIndex लौटाता है।

## String::IndexOf(const String\&, int, int, System::StringComparison) const method

सबस्ट्रिंग आगे की खोज।

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | खोज के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में लुकअप शुरू करने की स्थिति। |
| count | int | देखने के लिए अक्षरों की संख्या। |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### रिटर्न वैल्यू

[Index](../../index/) पहला पाया गया सबस्ट्रिंग का या -1 यदि नहीं मिला। खाली लुकअप स्ट्रिंग के लिए, हमेशा startIndex लौटाता है।

## String::IndexOf(const String\&, int, int) const method

सबस्ट्रिंग आगे की खोज।

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | खोज के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में लुकअप शुरू करने की स्थिति। |
| count | int | देखने के लिए अक्षरों की संख्या। |

### रिटर्न वैल्यू

[Index](../../index/) पहला पाया गया सबस्ट्रिंग का या -1 यदि नहीं मिला। खाली लुकअप स्ट्रिंग के लिए, हमेशा startIndex लौटाता है।

## संबंधित देखें

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)