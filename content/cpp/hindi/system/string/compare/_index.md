---
title: Compare()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: कम-बराबर-ज़्यादा दो उपस्ट्रिंग की तुलना करता है।
type: docs
weight: 820
url: /hi/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) मेथड


कम-बराबर-ज़्यादा दो उपस्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| indexA | int | पहली स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| indexB | int | दूसरी स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| length | int | तुलना के लिए वर्णों की संख्या। |
| ignoreCase | **bool** | निर्दिष्ट करता है कि तुलना केस-इनसेंसिटिव है या नहीं। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) मेथड


कम-बराबर-ज़्यादा दो उपस्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| indexA | int | पहली स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| indexB | int | दूसरी स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| length | int | तुलना के लिए वर्णों की संख्या। |
| ignoreCase | **bool** | निर्दिष्ट करता है कि तुलना केस-इनसेंसिटिव है या नहीं। |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | तुलना के लिए उपयोग किया जाने वाला कल्चर। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::Compare(const String\&, const String\&, System::StringComparison) मेथड


कम-बराबर-ज़्यादा दो स्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) मेथड


कम-बराबर-ज़्यादा दो स्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| indexA | int | पहली स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| indexB | int | दूसरी स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| length | int | तुलना के लिए वर्णों की संख्या। |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) मोड। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::Compare(const String\&, const String\&, bool) मेथड


कम-बराबर-ज़्यादा दो स्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| ignoreCase | **bool** | निर्दिष्ट करता है कि तुलना केस-इनसेंसिटिव है या नहीं। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) मेथड


कम-बराबर-ज़्यादा दो स्ट्रिंग की तुलना करता है।

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रинг। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| ignoreCase | **bool** | निर्दिष्ट करता है कि तुलना केस-इनसेंसिटिव है या नहीं। |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | तुलना के लिए उपयोग किया जाने वाला कल्चर। |

### वापसी मान

पहली उपस्ट्रिंग दूसरी से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## संबंधित देखें

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)