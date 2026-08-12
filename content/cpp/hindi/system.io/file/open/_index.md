---
title: Open()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ाइल को निर्दिष्ट मोड में पढ़ने और लिखने के लिए खोलता है तथा बिना शेयरिंग के।
type: docs
weight: 235
url: /hi/system.io/file/open/
---
## File::Open(const String\&, FileMode) मेथड

निर्दिष्ट फ़ाइल को निर्दिष्ट मोड में पढ़ने और लिखने के लिए खोलता है तथा बिना शेयरिंग के।

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को खोलने का पथ |
| mode | [FileMode](../../filemode/) | फ़ाइल को खोलने के मोड को निर्दिष्ट करता है |

### रिटर्न वैल्यू

एक [FileStream](../../filestream/) ऑब्जेक्ट जो खुले फ़ाइल से जुड़ा है

## File::Open(const String\&, FileMode, FileAccess, FileShare) मेथड

निर्दिष्ट फ़ाइल को निर्दिष्ट मोड में, निर्दिष्ट एक्सेस टाइप और शेयरिंग विकल्प के साथ खोलता है।

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को खोलने का पथ |
| mode | [FileMode](../../filemode/) | फ़ाइल को खोलने के मोड को निर्दिष्ट करता है |
| access | [FileAccess](../../fileaccess/) | वांछित एक्सेस टाइप |
| share | [FileShare](../../fileshare/) | अन्य [FileStream](../../filestream/) ऑब्जेक्ट्स के पास खुले फ़ाइल तक पहुँच का प्रकार |

### रिटर्न वैल्यू

एक [FileStream](../../filestream/) ऑब्जेक्ट जो खुले फ़ाइल से जुड़ा है

## संबंधित देखें

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)