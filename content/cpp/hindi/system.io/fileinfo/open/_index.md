---
title: Open()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाई गई फ़ाइल को निर्दिष्ट मोड में पढ़ने और लिखने के लिए खोलता है तथा बिना किसी शेयरिंग के।
type: docs
weight: 183
url: /hi/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल को निर्दिष्ट मोड में पढ़ने और लिखने के लिए खोलता है और बिना किसी साझा के।

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | फ़ाइल को खोलने के लिए मोड निर्दिष्ट करता है |

### Return Value

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल से जुड़ा एक [FileStream](../../filestream/) ऑब्जेक्ट

## FileInfo::Open(FileMode, FileAccess) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल को निर्दिष्ट मोड में, निर्दिष्ट एक्सेस प्रकार के साथ और बिना साझा के खोलता है।

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | फ़ाइल को खोलने के लिए मोड निर्दिष्ट करता है |
| access | [FileAccess](../../fileaccess/) | अनुरोधित एक्सेस प्रकार |

### Return Value

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल से जुड़ा एक [FileStream](../../filestream/) ऑब्जेक्ट

## FileInfo::Open(FileMode, FileAccess, FileShare) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल को निर्दिष्ट मोड में, निर्दिष्ट एक्सेस प्रकार और साझा विकल्प के साथ खोलता है।

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | फ़ाइल को खोलने के लिए मोड निर्दिष्ट करता है |
| access | [FileAccess](../../fileaccess/) | अनुरोधित एक्सेस प्रकार |
| share | [FileShare](../../fileshare/) | अन्य [FileStream](../../filestream/) ऑब्जेक्ट्स द्वारा खुले फ़ाइल तक पहुँच का प्रकार |

### Return Value

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित फ़ाइल से जुड़ा एक [FileStream](../../filestream/) ऑब्जेक्ट

## देखें

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* क्लास [FileInfo](../)
* नामस्थान [System::IO](../../)
* Library [Aspose.Slides](../../../)