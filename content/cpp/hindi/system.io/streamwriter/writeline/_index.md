---
title: WriteLine()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम में लाइन टर्मिनेटर अक्षरों को लिखता है।
type: docs
weight: 92
url: /hi/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() मेथड

स्ट्रीम में लाइन टर्मिनेटर अक्षरों को लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) मेथड

निर्दिष्ट स्ट्रिंग को, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | लिखने के लिए स्ट्रिंग |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) मेथड

निर्दिष्ट ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | लिखने के लिए ऑब्जेक्ट |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) मेथड

निर्दिष्ट ऐरे से सभी अक्षर लिखता है, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | लिखने के लिए अक्षर रखने वाला ऐरे |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) मेथड

निर्दिष्ट कैरैक्टर ऐरे से UTF-16 अक्षरों की निर्दिष्ट सबरेन्ज़ लिखता है, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | लिखने के लिए अक्षर रखने वाला ऐरे |
| index | **int32_t** | **buffer** में सबरेन्ज़ की शुरुआत का 0-आधारित इंडेक्स |
| count | **int32_t** | लिखने के लिए सबरेन्ज़ में अक्षरों की संख्या; -1 का मतलब है कि सबरेन्ज़ **buffer** ऐरे के अंत तक रहता है |

## StreamWriter::WriteLine(const char_t *) मेथड

निर्दिष्ट C-स्ट्रिंग को, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const char_t * | लिखने के लिए C-स्ट्रिंग |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) मेथड

निर्दिष्ट ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, उसके बाद लाइन-टर्मिनेटिंग अक्षरों को, स्ट्रीम में लिखता है।

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | ऑब्जेक्ट का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | लिखने के लिए ऑब्जेक्ट |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [StreamWriter](../)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)