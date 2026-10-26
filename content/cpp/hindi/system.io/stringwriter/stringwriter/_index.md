---
title: StringWriter()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट StringBuilder और IFormatProvider का उपयोग करके StringWriter का नया उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) कंस्ट्रक्टर

निर्दिष्ट StringBuilder और [IFormatProvider](../../../system/iformatprovider/) का उपयोग करके [StringWriter](../) का नया उदाहरण बनाता है।

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | निर्मित [StringWriter](../) द्वारा उपयोग किया जाने वाला StringBuilder ऑब्जेक्ट |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | निर्मित ऑब्जेक्ट द्वारा उपयोग किया जाने वाला [IFormatProvider](../../../system/iformatprovider/) ऑब्जेक्ट |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) कंस्ट्रक्टर

निर्दिष्ट StringBuilder और वर्तमान संस्कृति से [IFormatProvider](../../../system/iformatprovider/) का उपयोग करके [StringWriter](../) का नया उदाहरण बनाता है।

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | निर्मित [StringWriter](../) द्वारा उपयोग किया जाने वाला StringBuilder ऑब्जेक्ट |

## StringWriter::StringWriter(const IFormatProviderPtr\&) कंस्ट्रक्टर

निर्दिष्ट [IFormatProvider](../../../system/iformatprovider/) का उपयोग करके [StringWriter](../) का नया उदाहरण बनाता है।

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | निर्मित ऑब्जेक्ट द्वारा उपयोग किया जाने वाला [IFormatProvider](../../../system/iformatprovider/) ऑब्जेक्ट |

## StringWriter::StringWriter() कंस्ट्रक्टर

वर्तमान संस्कृति से [IFormatProvider](../../../system/iformatprovider/) का उपयोग करके [StringWriter](../) का नया उदाहरण बनाता है।

```cpp
System::IO::StringWriter::StringWriter()
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* क्लास [StringBuilder](../../../system.text/stringbuilder/)
* क्लास [StringWriter](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)