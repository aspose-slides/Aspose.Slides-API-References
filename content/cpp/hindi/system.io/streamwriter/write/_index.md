---
title: Write()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अक्षर को स्ट्रीम में लिखता है।
type: docs
weight: 79
url: /hi/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) विधि

निर्दिष्ट अक्षर को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | char_t | लिखने के लिये अक्षर |

## StreamWriter::Write(const String\&) विधि

निर्दिष्ट स्ट्रिंग को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | लिखने के लिये स्ट्रिंग |

## StreamWriter::Write(const SharedPtr\<Object\>\&) विधि

निर्दिष्ट ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | लिखने के लिये ऑब्जेक्ट |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) विधि

निर्दिष्ट एरे से सभी अक्षरों को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | लिखने के लिये अक्षरों को सम्मिलित करने वाला एरे |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट एरे से यूटीएफ-16 अक्षरों की उप-श्रेणी को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | लिखने के लिये अक्षरों को सम्मिलित करने वाला एरे |
| index | **int32_t** | **buffer** में वह 0-आधारित इंडेक्स जहां से उप-श्रेणी लिखना प्रारम्भ होता है |
| count | **int32_t** | लिखने के लिये उप-श्रेणी में अक्षरों की संख्या; -1 का अर्थ है कि उप-श्रेणी **buffer** एरे के अंत तक विस्तारित होती है |

## StreamWriter::Write(const char_t *) विधि

निर्दिष्ट C-स्ट्रींग को स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const char_t * | लिखने के लिये C-स्ट्रींग |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) विधि

निर्दिष्ट ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है।

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | लिखने के लिये ऑब्जेक्ट |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [StreamWriter](../)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)