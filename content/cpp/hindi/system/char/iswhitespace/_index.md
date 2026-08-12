---
title: IsWhiteSpace()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि निर्दिष्ट वर्ण बफ़र में निर्दिष्ट सूचकांक पर स्थित वर्ण को श्वेत स्थान वर्ण के रूप में वर्गीकृत किया गया है या नहीं।
type: docs
weight: 157
url: /hi/system/char/iswhitespace/
---
## Char::IsWhiteSpace(const char_t *, int) विधि

निर्धारित करता है कि निर्दिष्ट चर बफ़र में निर्दिष्ट सूचकांक पर स्थित वर्ण को श्वेत स्थान वर्ण के रूप में वर्गीकृत किया गया है या नहीं।

```cpp
static bool System::Char::IsWhiteSpace(const char_t *str, int idx)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const char_t * | वर्ण बफ़र की शुरुआत के लिए पॉइंटर |
| idx | int | परीक्षण किए जाने वाले वर्ण के लिये निर्दिष्ट बफ़र में शून्य-आधारित सूचकांक |

### रिटर्न वैल्यू

True if the character at the specified index is a white space character, otherwise - false

## Char::IsWhiteSpace(char_t) विधि

निर्धारित करता है कि निर्दिष्ट वर्ण को श्वेत स्थान वर्ण के रूप में वर्गीकृत किया गया है या नहीं।

```cpp
static bool System::Char::IsWhiteSpace(char_t c)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | char_t | परीक्षण किया जाने वाला वर्ण |

### रिटर्न वैल्यू

True if the specified character is a white space character, otherwise - false

## Char::IsWhiteSpace(const String\&, int) विधि

निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर स्थित वर्ण को श्वेत स्थान वर्ण के रूप में वर्गीकृत किया गया है या नहीं।

```cpp
static bool System::Char::IsWhiteSpace(const String &str, int index)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../string/)\& | एक स्ट्रिंग |
| index | int | निर्दिष्ट स्ट्रिंग में शून्य-आधारित सूचकांक |

### रिटर्न वैल्यू

True if the character at the specified index is a white space character, otherwise - false

## देखें भी

* क्लास [Char](../)
* क्लास [String](../../string/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)