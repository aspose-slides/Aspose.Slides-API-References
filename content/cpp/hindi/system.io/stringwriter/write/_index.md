---
title: Write()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट अक्षर को स्ट्रीम में लिखता है।
type: docs
weight: 40
url: /hi/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) विधि

निर्दिष्ट अक्षर को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | char_t | लिखने के लिये मूल्य |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट अक्षर सरणी से निर्दिष्ट उप-सीमा के अक्षरों को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | लिखने के लिये अक्षर वाला सरणी |
| index | **int32_t** | **buffer** में वह 0-आधारित सूचकांक जहाँ से उप-सीमा लिखना शुरू होती है |
| count | **int32_t** | लिखने के लिये उप-सीमा में अक्षरों की संख्या |

## StringWriter::Write(const String\&) विधि

निर्दिष्ट स्ट्रिंग को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | लिखने के लिये स्ट्रिंग |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [StringWriter](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)