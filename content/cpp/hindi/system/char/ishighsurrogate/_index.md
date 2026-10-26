---
title: IsHighSurrogate()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में निर्दिष्ट इंडेक्स पर स्थित अक्षर UTF-16 हाई सरोगेट कोड यूनिट है या नहीं।
type: docs
weight: 40
url: /hi/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) विधि

निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में निर्दिष्ट इंडेक्स पर स्थित अक्षर UTF-16 हाई सरोगेट कोड यूनिट है या नहीं।

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | एक स्ट्रिंग |
| index | int | परीक्षण किए जाने वाले अक्षर का निर्दिष्ट स्ट्रिंग में इंडेक्स |

### रिटर्न मान

True if the character at the specified index is a UTF-16 high surrogate code unit, otherwise - false

## Char::IsHighSurrogate(const char_t *, int) विधि

निर्धारित करता है कि निर्दिष्ट कैरेक्टर बफ़र में निर्दिष्ट इंडेक्स पर स्थित अक्षर हाई सरोगेट है या नहीं।

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const char_t * | कैरेक्टर बफ़र की शुरुआत की ओर संकेतक |
| idx | int | परीक्षण किए जाने वाले अक्षर का बफ़र में शून्य-आधारित इंडेक्स |

### रिटर्न मान

True if the character at the specified index is a high surrogate, otherwise - false

## Char::IsHighSurrogate(char_t) विधि

निर्धारित करता है कि निर्दिष्ट अक्षर हाई सरोगेट है या नहीं।

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | char_t | परीक्षण किया जाने वाला अक्षर |

### रिटर्न मान

True if the specified character is a high surrogate, otherwise - false

## देखें

* क्लास [String](../../string/)
* क्लास [Char](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)