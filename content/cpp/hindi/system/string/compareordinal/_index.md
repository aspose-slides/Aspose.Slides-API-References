---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API संदर्भ
description: Ordinal मोड का उपयोग करके दो स्ट्रिंग्स की कम-बराबर-ज़्यादा तुलना करता है।
type: docs
weight: 833
url: /hi/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) विधि

Less-equal-greater दो स्ट्रिंग्स की तुलना क्रमिक मोड का उपयोग करके करता है।

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |

### वापसी मान

यदि प्रथम उपस्ट्रिंग दूसरा से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## String::CompareOrdinal(const String\&, int, const String\&, int, int) विधि

Less-equal-greater दो स्ट्रिंग्स की तुलना क्रमिक मोड का उपयोग करके करता है।

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| strA | const [String](../)\& | तुलना के लिए पहली स्ट्रिंग। |
| indexA | int | पहली स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| strB | const [String](../)\& | तुलना के लिए दूसरी स्ट्रिंग। |
| indexB | int | दूसरी स्ट्रिंग उपस्ट्रिंग की शुरुआत। |
| length | int | तुलना के लिए अक्षरों की संख्या। |

### वापसी मान

यदि प्रथम उपस्ट्रिंग दूसरा से कम है तो नकारात्मक मान, यदि समान हों तो शून्य, अन्यथा सकारात्मक मान।

## संबंधित देखें

* क्लास [String](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)