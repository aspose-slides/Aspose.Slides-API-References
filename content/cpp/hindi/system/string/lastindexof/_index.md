---
title: LastIndexOf()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: उपस्ट्रिंग का पीछे की ओर खोज।
type: docs
weight: 651
url: /hi/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const विधि

सबस्ट्रिंग पीछे की खोज।

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | देखने के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में वह स्थिति जहाँ से खोज शुरू करनी है। |

### वापसी मान

[Index](../../index/) अंतिम मिली सबस्ट्रिंग का इंडेक्स या न मिलने पर -1। खाली लुकअप स्ट्रिंग के लिए, हमेशा स्ट्रिंग की लंबाई लौटाता है।

## String::LastIndexOf(const String\&, System::StringComparison) const विधि

सबस्ट्रिंग पीछे की खोज।

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | देखने के लिए सबस्ट्रिंग। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### वापसी मान

[Index](../../index/) अंतिम मिली सबस्ट्रिंग का इंडेक्स या यदि नहीं मिला तो -1। खाली लुकअप स्ट्रिंग के लिए, हमेशा स्ट्रिंग की लंबाई लौटाता है।

## String::LastIndexOf(const String\&, int, System::StringComparison) const विधि

सबस्ट्रिंग पीछे की खोज।

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | देखने के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में वह स्थिति जहाँ से खोज शुरू करनी है। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### वापसी मान

[Index](../../index/) अंतिम मिली सबस्ट्रिंग का इंडेक्स या यदि नहीं मिला तो -1। खाली लुकअप स्ट्रिंग के लिए, हमेशा स्ट्रिंग की लंबाई लौटाता है।

## String::LastIndexOf(const String\&, int, int, StringComparison) const विधि

सबस्ट्रिंग पीछे की खोज।

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../)\& | देखने के लिए सबस्ट्रिंग। |
| startIndex | int | स्रोत स्ट्रिंग में वह स्थिति जहाँ से खोज शुरू करनी है। |
| count | int | देखे जाने वाले अक्षरों की संख्या। |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### वापसी मान

[Index](../../index/) अंतिम मिली सबस्ट्रिंग का इंडेक्स या यदि नहीं मिला तो -1। खाली लुकअप स्ट्रिंग के लिए, हमेशा startIndex+count लौटाता है।

## String::LastIndexOf(char_t) const विधि

अक्षर पीछे की खोज।

```cpp
int System::String::LastIndexOf(char_t value) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char_t | देखने के लिए अक्षर। |

### वापसी मान

[Index](../../index/) अंतिम अक्षर की स्थिति या यदि नहीं मिला तो -1।

## String::LastIndexOf(char_t, int32_t) const विधि

अक्षर पीछे की खोज।

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char_t | देखने के लिए अक्षर। |
| startIndex | **int32_t** | [Index](../../index/) पर खोज शुरू करने के लिए। |

### वापसी मान

[Index](../../index/) startIndex के बाद अंतिम अक्षर की स्थिति या यदि नहीं मिला तो -1।

## String::LastIndexOf(char_t, int32_t, int32_t) const विधि

अक्षर पीछे की खोज।

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char_t | देखने के लिए अक्षर। |
| startIndex | **int32_t** | [Index](../../index/) पर खोज शुरू करने के लिए। |
| count | **int32_t** | देखे जाने वाले अक्षरों की संख्या। |

### वापसी मान

[Index](../../index/) startIndex के बाद अंतिम अक्षर की स्थिति या यदि नहीं मिला तो -1।

## देखें

* Enum [StringComparison](../../stringcomparison/)
* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)