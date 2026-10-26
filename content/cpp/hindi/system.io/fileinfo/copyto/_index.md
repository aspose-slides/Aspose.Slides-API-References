---
title: CopyTo()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा दर्शाई गई फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि गंतव्य फ़ाइल पहले से मौजूद है, तो प्रतिलिपि बनाना विफल हो जाता है।
type: docs
weight: 105
url: /hi/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाई गई फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि गंतव्य फ़ाइल पहले से मौजूद है, तो प्रतिलिपि बनाना विफल हो जाता है।

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | गंतव्य फ़ाइल का नाम |

### रिटर्न वैल्यू

एक [FileInfo](../) ऑब्जेक्ट जो कॉपी का प्रतिनिधित्व करता है

## FileInfo::CopyTo(const String\&, bool) मेथड

वर्तमान ऑब्जेक्ट द्वारा दर्शाई गई फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। एक पैरामीटर यह निर्धारित करता है कि मौजूदा गंतव्य फ़ाइल को अधिलेखित किया जाना चाहिए या नहीं।

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | गंतव्य फ़ाइल का नाम |
| overwrite | **bool** | यदि मौजूदा गंतव्य फ़ाइल को अधिलेखित किया जाना चाहिए तो true, अन्यथा false, यानी यदि गंतव्य फ़ाइल पहले से मौजूद है तो कॉपी विफल हो जाएगी |

### रिटर्न वैल्यू

एक [FileInfo](../) ऑब्जेक्ट जो कॉपी का प्रतिनिधित्व करता है

## संबंधित देखें

* टाइपडिफ़ [FileInfoPtr](../../../system/fileinfoptr/)
* क्लास [String](../../../system/string/)
* क्लास [FileInfo](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)