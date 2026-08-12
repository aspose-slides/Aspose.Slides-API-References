---
title: Compare()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग्स की तुलना करता है। लागू नहीं है।
type: docs
weight: 66
url: /hi/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method


स्ट्रिंग्स की तुलना करता है। लागू नहीं है।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | बाएँ हाथ की स्ट्रिंग। |
| string2 | const [String](../../../system/string/)\& | दाएँ हाथ की स्ट्रिंग। |

### रिटर्न मान

यदि LHS स्ट्रिंग RHS से पहले आती है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method


स्ट्रिंग्स की तुलना करता है। केवल Ordinal और OrdinalIgnoreCase मोड्स समर्थित हैं।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | बाएँ हाथ की स्ट्रिंग। |
| b | const [String](../../../system/string/)\& | दाएँ हाथ की स्ट्रिंग। |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) तुलना प्रकार। |

### रिटर्न मान

यदि LHS स्ट्रिंग RHS से पहले आती है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method


एक स्ट्रिंग के एक सेक्शन की तुलना दूसरे स्ट्रिंग के सेक्शन से करता है। लागू नहीं है।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | पहली स्ट्रिंग। |
| offset1 | int | **string1** में अक्षरों का प्रारम्भिक सूचकांक। |
| length1 | int | **string1** में तुलना करने के लिए अक्षरों की संख्या। |
| string2 | const [String](../../../system/string/)\& | दूसरी स्ट्रिंग। |
| offset2 | int | **string2** में अक्षरों का प्रारम्भिक सूचकांक। |
| length2 | int | **string2** में तुलना करने के लिए अक्षरों की संख्या। |

### रिटर्न मान

यदि पहला स्ट्रिंग सेक्शन दूसरा स्ट्रिंग सेक्शन से पहले आता है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method


स्ट्रिंग तुलना तरीकों का उपयोग करके एक स्ट्रिंग के अंत सेक्शन की तुलना दूसरे स्ट्रिंग के अंत सेक्शन से करता है। लागू नहीं है।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | पहली स्ट्रिंग। |
| offset1 | int | **string1** में अक्षरों का प्रारम्भिक सूचकांक। |
| string2 | const [String](../../../system/string/)\& | दूसरी स्ट्रिंग। |
| offset2 | int | **string2** में अक्षरों का प्रारम्भिक सूचकांक। |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) तुलना विकल्प। |

### रिटर्न मान

यदि पहला स्ट्रिंग सेक्शन दूसरा स्ट्रिंग सेक्शन से पहले आता है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## CompareInfo::Compare(const String\&, int, const String\&, int) const method


एक स्ट्रिंग के अंत सेक्शन की तुलना दूसरे स्ट्रिंग के अंत सेक्शन से करता है। लागू नहीं है।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | पहली स्ट्रिंग। |
| offset1 | int | **string1** में अक्षरों का प्रारम्भिक सूचकांक। |
| string2 | const [String](../../../system/string/)\& | दूसरी स्ट्रिंग। |
| offset2 | int | **string2** में अक्षरों का प्रारम्भिक सूचकांक। |

### रिटर्न मान

यदि पहला स्ट्रिंग सेक्शन दूसरा स्ट्रिंग सेक्शन से पहले आता है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method


स्ट्रिंग तुलना तरीकों का उपयोग करके एक स्ट्रिंग के सेक्शन की तुलना दूसरे स्ट्रिंग के सेक्शन से करता है। लागू नहीं है।

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | पहली स्ट्रिंग। |
| offset1 | int | **string1** में अक्षरों का प्रारम्भिक सूचकांक। |
| length1 | int | **string1** में तुलना करने के लिए अक्षरों की संख्या। |
| string2 | const [String](../../../system/string/)\& | दूसरी स्ट्रिंग। |
| offset2 | int | **string2** में अक्षरों का प्रारम्भिक सूचकांक। |
| length2 | int | **string2** में तुलना करने के लिए अक्षरों की संख्या। |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) तुलना विकल्प। |

### रिटर्न मान

यदि पहला स्ट्रिंग सेक्शन दूसरा स्ट्रिंग सेक्शन से पहले आता है तो नकारात्मक मान, समान होने पर शून्य, अन्यथा धनात्मक मान।

## संबंधित देखें

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)