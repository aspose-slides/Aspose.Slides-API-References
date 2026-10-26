---
title: AppendFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़ॉर्मेटेड स्ट्रिंग को बिल्डर में जोड़ता है।
type: docs
weight: 131
url: /hi/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) मेथड

फ़ॉर्मेटेड स्ट्रिंग को बिल्डर में जोड़ता है।

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TArgs | Arguments type. |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### वापसी मान

This pointer.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) मेथड

फ़ॉर्मेटेड स्ट्रिंग को बिल्डर में जोड़ता है।

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TArgs | Arguments type. |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Format provider; ignored. |
| format | const [String](../../../system/string/)\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### वापसी मान

This pointer.

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [StringBuilder](../)
* क्लास [String](../../../system/string/)
* क्लास [IFormatProvider](../../../system/iformatprovider/)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)