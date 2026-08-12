---
title: ToChar()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException को फेंकता है।
type: docs
weight: 118
url: /hi/system/convert/tochar/
---
## Convert::ToChar(bool) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) विधि

निर्दिष्ट 8-बिट अनसाइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) विधि

निर्दिष्ट 8-बिट साइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) विधि

निर्दिष्ट 16-बिट अनसाइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) विधि

निर्दिष्ट 16-बिट साइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) विधि

निर्दिष्ट 32-बिट अनसाइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) विधि

निर्दिष्ट 32-बिट साइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) विधि

निर्दिष्ट 64-बिट अनसाइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) विधि

निर्दिष्ट 64-बिट साइन्ड इंटीजर को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) विधि

निर्दिष्ट unicode अक्षर को लौटाता है।

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) विधि

रूपांतरण समर्थित नहीं है। हमेशा InvalidCastException फेंकता है।

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) विधि

निर्दिष्ट c-string के पहले और एकमात्र अक्षर को char_t मान में बदलता है।

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### आर्ग्युमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const char_t * | कनवर्ट करने के लिए c-string; अपेक्षा है कि c-string बिल्कुल 1 अक्षर लंबा हो। |

### रिटर्न वैल्यू

निर्दिष्ट c-string का पहला और एकमात्र अक्षर यदि यह बिल्कुल 1 characetr लंबा हो, अन्यथा - 0

## Convert::ToChar(const String\&) विधि

निर्दिष्ट स्ट्रिंग के पहले और एकमात्र अक्षर को char_t मान में बदलता है।

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### आर्ग्युमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | कनवर्ट करने के लिए स्ट्रिंग; अपेक्षा है कि स्ट्रिंग बिल्कुल 1 अक्षर लंबा हो |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग का पहला और एकमात्र अक्षर यदि यह बिल्कुल 1 characetr लंबा हो, अन्यथा - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट स्ट्रिंग के पहले और एकमात्र अक्षर को char_t मान में बदलता है।

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### आर्ग्युमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | कनवर्ट करने के लिए स्ट्रिंग; अपेक्षा है कि स्ट्रिंग बिल्कुल 1 अक्षर लंबा हो |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग का पहला और एकमात्र अक्षर यदि यह बिल्कुल 1 characetr लंबा हो, अन्यथा - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट बॉक्स्ड मान को समकक्ष unicode अक्षर में बदलता है।

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### आर्ग्युमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | कनवर्ट करने के लिए मान को बॉक्स करने वाले ऑब्जेक्ट का साझा पॉइंटर |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | यदि बॉक्स्ड मान का प्रकार [String](../../string/) हो तो उपयोग किया जाने वाला स्ट्रिंग फ़ॉर्मेट |

### रिटर्न वैल्यू

निर्दिष्ट बॉक्स्ड मान के बराबर एक unicode अक्षर

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* वर्ग [Decimal](../../decimal/)
* वर्ग [DateTime](../../datetime/)
* वर्ग [String](../../string/)
* वर्ग [IFormatProvider](../../iformatprovider/)
* वर्ग [Object](../../object/)
* संरचना [Convert](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)