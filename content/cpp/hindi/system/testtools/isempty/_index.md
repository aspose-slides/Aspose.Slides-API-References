---
title: IsEmpty()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि स्ट्रिंग खाली है।
type: docs
weight: 14
url: /hi/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) विधि

स्ट्रिंग खाली है या नहीं जाँचता है।

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) खाली होने की जाँच के लिए। |

### वापसी मान

True if string is empty (null-length), false otherwise.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) विधि

कलेक्शन खाली है या नहीं जाँचता है।

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कलेक्शन प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | जाँच करने के लिये collection। |

### वापसी मान

True if collection has zero element count, false otherwise.

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* स्ट्रक्ट [TestTools](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)