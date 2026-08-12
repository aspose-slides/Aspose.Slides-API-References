---
title: Split()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्ट्रिंग को अक्षर द्वारा विभाजित करता है।
type: docs
weight: 768
url: /hi/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const विधि

स्ट्रिंग को अक्षर द्वारा विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | स्ट्रिंग को विभाजित करने के लिए अक्षर। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(char_t, int32_t, StringSplitOptions) const विधि

स्ट्रिंग को अक्षर द्वारा विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | स्ट्रिंग को विभाजित करने के लिए अक्षर। |
| count | **int32_t** | वापसी के लिए अधिकतम उपस्ट्रिंग्स की संख्या। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(char_t, char_t, StringSplitOptions) const विधि

स्ट्रिंग को दो में से एक अक्षर द्वारा विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separatorA | char_t | स्ट्रिंग को विभाजित करने के लिए पहला अक्षर। |
| separatorB | char_t | स्ट्रिंग को विभाजित करने के लिए दूसरा अक्षर। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const विधि

निर्दिष्ट अक्षरों में से एक द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) विभाजक अक्षरों का। यदि खाली है, तो कोई भी whitespace अक्षर विभाजक माना जाएगा। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const विधि

निर्दिष्ट अक्षरों में से एक द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) विभाजक अक्षरों का। यदि खाली है, तो कोई भी whitespace अक्षर विभाजक माना जाएगा। |
| count | **int32_t** | वापसी के लिए अधिकतम उपस्ट्रिंग्स की संख्या। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const String\&, StringSplitOptions) const विधि

उपस्ट्रिंग द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | विभाजक के रूप में कार्य करने वाली उपस्ट्रिंग। यदि खाली है, तो whitespace अक्षर विभाजक के रूप में कार्य करता है। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const String\&, int, StringSplitOptions) const विधि

उपस्ट्रिंग द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | विभाजक के रूप में कार्य करने वाली उपस्ट्रिंग। यदि खाली है, तो whitespace अक्षर विभाजक के रूप में कार्य करता है। |
| count | int | स्प्लिट एरे में अधिकतम तत्वों की संख्या। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const विधि

उपस्ट्रिंग द्वारा स्ट्रिंग को विभाजित करता है।

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) विभाजक स्ट्रिंग्स का। यदि खाली है, तो कोई विभाजन नहीं किया जाता। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const विधि

उपस्ट्रिंग द्वारा स्ट्रिंग को विभाजित करता है। वर्तमान में, यह केवल शून्य या एक तत्व वाले विभाजकों के एरे को समर्थन देता है।

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) विभाजक स्ट्रिंग्स का। यदि खाली है, तो कोई विभाजन नहीं किया जाता। |
| count | int | स्प्लिट एरे में अधिकतम तत्वों की संख्या। |
| opt | [StringSplitOptions](../../stringsplitoptions/) | विभाजन विकल्प। |

### रिटर्न वैल्यू

[Array](../../array/) उपस्ट्रिंग्स।

## See Also

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)