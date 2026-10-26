---
title: Replace()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक फ़ाइल की सामग्री को दूसरी फ़ाइल से बदलता है और बदली गई फ़ाइल का बैकअप बनाता है।
type: docs
weight: 339
url: /hi/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) विधि

एक फ़ाइल की सामग्री को दूसरी फ़ाइल से बदलता है और बदली गई फ़ाइल का बैकअप बनाता है।

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | फ़ाइल को बदलने के लिये नाम |
| destinationFileName | const [String](../../../system/string/)\& | फ़ाइल को बदलने के लिये नाम |
| destinationBackupFileName | const [String](../../../system/string/)\& | बैकअप फ़ाइल का नाम |
| ignoreMetadataErrors | **bool** | निर्दिष्ट करता है कि बदली गई फ़ाइल से प्रतिस्थापन फ़ाइल में मर्ज त्रुटियों को (true) अनदेखा किया जाना चाहिए या (false) नहीं |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)