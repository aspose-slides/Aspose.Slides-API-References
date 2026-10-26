---
title: FileStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पैरामीटरों के साथ FileStream क्लास का एक नया उदाहरण बनाता है और उसे प्रारंभ करता है।
type: docs
weight: 1
url: /hi/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) निर्माता


निर्दिष्ट पैरामीटरों के साथ [FileStream](../) क्लास का एक नया उदाहरण बनाता है और उसे प्रारंभ करता है।

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को खोलने के लिए पथ। |
| mode | [FileMode](../../filemode/) | फ़ाइल खोलने के लिए मोड निर्धारित करता है। |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) निर्माता


निर्दिष्ट पैरामीटरों के साथ [FileStream](../) क्लास का एक नया उदाहरण बनाता है और उसे प्रारंभ करता है।

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को खोलने के लिए पथ। |
| mode | [FileMode](../../filemode/) | फ़ाइल खोलने के लिए मोड निर्धारित करता है। |
| access | [FileAccess](../../fileaccess/) | अनुरोधित अभिगम प्रकार। |
| share | [FileShare](../../fileshare/) | अन्य [FileStream](../) वस्तुओं द्वारा खुले फ़ाइल तक पहुंच का प्रकार। |
| buffer_size | **int32_t** | पढ़ने और लिखने के संचालन के दौरान बफ़र की गई बाइटों की संख्या। |
| options | [FileOptions](../../fileoptions/) | अतिरिक्त विकल्प। |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) निर्माता


निर्दिष्ट पैरामीटरों के साथ [FileStream](../) क्लास का एक नया उदाहरण बनाता है और उसे प्रारंभ करता है।

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को खोलने के लिए पथ। |
| mode | [FileMode](../../filemode/) | फ़ाइल खोलने के लिए मोड निर्धारित करता है। |
| access | [FileAccess](../../fileaccess/) | अनुरोधित अभिगम प्रकार। |
| share | [FileShare](../../fileshare/) | अन्य [FileStream](../) वस्तुओं द्वारा खुले फ़ाइल तक पहुंच का प्रकार। |
| buffer_size | **int32_t** | पढ़ने और लिखने के संचालन के दौरान बफ़र की गई बाइटों की संख्या। |
| useAsync | **bool** | असिंक्रोनस I/O या सिंक्रोनस I/O उपयोग करने के लिये निर्धारित करता है। |

## टिप्पणियाँ



अधिनिर्मित ऑपरेटिंग सिस्टम असिंक्रोनस I/O को समर्थन नहीं दे सकता है। 

## FileStream::FileStream(const FileStream\&) निर्माता




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## देखें

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* क्लास [String](../../../system/string/)
* क्लास [FileStream](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)