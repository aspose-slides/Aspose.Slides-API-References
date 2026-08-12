---
title: Equals()
second_title: Aspose.Slides for C++ API संदर्भ
description: String समानता तुलना। StringComparison enumeration द्वारा प्रदान किए गए कई मोड समर्थित हैं।
type: docs
weight: 391
url: /hi/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const विधि

[String](../) समानता तुलना। StringComparison enumeration द्वारा प्रदान किए गए कई मोड समर्थित हैं।

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) को वर्तमान वाले के विरुद्ध तुलना करने के लिए। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड (विवरण के लिए [System::StringComparison](../../stringcomparison/) देखें)। |

### रिटर्न वैल्यू

यदि स्ट्रिंग्स चयनित तुलना प्रकार का उपयोग करके मेल खाती हैं तो true, अन्यथा false।

## String::Equals(const String\&) const विधि

[String](../) समानता तुलना। [System::StringComparison::Ordinal](../../stringcomparison/) तुलना मोड का उपयोग करता है।

```cpp
bool System::String::Equals(const String &str) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) को वर्तमान वाले के विरुद्ध तुलना करने के लिए। |

### रिटर्न वैल्यू

यदि स्ट्रिंग्स मेल खाती हैं तो true, अन्यथा false।

## String::Equals(const String\&, const String\&) विधि

दो स्ट्रिंग्स को Ordial तुलना मोड का उपयोग करके समानता तुलना करता है।

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना करने के लिए पहली स्ट्रिंग। |
| strB | const [String](../)\& | तुलना करने के लिए दूसरी स्ट्रिंग। |

### रिटर्न वैल्यू

यदि स्ट्रिंग्स मेल खाती हैं तो true, अन्यथा false।

## String::Equals(const String\&, const String\&, System::StringComparison) विधि

दो स्ट्रिंग्स को समानता तुलना करता है।

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना करने के लिए पहली स्ट्रिंग। |
| strB | const [String](../)\& | तुलना करने के लिए दूसरी स्ट्रिंग। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### रिटर्न वैल्यू

यदि स्ट्रिंग्स मेल खाती हैं तो true, अन्यथा false।

## संबंधित देखें

* एनम [StringComparison](../../stringcomparison/)
* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)