---
title: CompareTo()
second_title: Aspose.Slides C++ के लिये API संदर्भ
description: निर्दिष्ट स्ट्रिंग तुलना नियमों के साथ दो कैरेक्टर स्पैन की तुलना करता है।
type: docs
weight: 404
url: /hi/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) फ़ंक्शन

निर्दिष्ट स्ट्रिंग तुलना नियमों के साथ दो कैरेक्टर स्पैन की तुलना करता है।

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | पहला कैरेक्टर स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | दूसरा कैरेक्टर स्पैन |
| comparisonType | [StringComparison](../../system/stringcomparison/) | किए जाने वाले स्ट्रिंग तुलना का प्रकार |

### रिटर्न वैल्यू

यदि स्पैन < अन्य हो तो नकारात्मक मान, यदि बराबर हो तो शून्य, यदि स्पैन > अन्य हो तो सकारात्मक मान

## संबंधित देखें

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)