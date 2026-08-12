---
title: Replace()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट गंतव्य फ़ाइल की सामग्री को वर्तमान FileInfo वस्तु द्वारा प्रतिनिधित्व किए गए फ़ाइल से बदलता है और बदली गई फ़ाइल का बैकअप बनाता है।
type: docs
weight: 131
url: /hi/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) मेथड

निर्दिष्ट लक्ष्य फ़ाइल की सामग्री को वर्तमान [FileInfo](../) वस्तु द्वारा प्रतिनिधित्व किए गए फ़ाइल से बदलता है और बदली गई फ़ाइल का बैकअप बनाता है।

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | फ़ाइल को बदलने के लिए नाम |
| destinationBackupFileName | const [String](../../../system/string/)\& | बैकअप फ़ाइल का नाम |

### रिटर्न वैल्यू

एक FileInfor वस्तु जो **destinationFileName** द्वारा इंगित फ़ाइल का प्रतिनिधित्व करती है

## FileInfo::Replace(const String\&, const String\&, bool) मेथड

निर्दिष्ट लक्ष्य फ़ाइल की सामग्री को वर्तमान [FileInfo](../) वस्तु द्वारा प्रतिनिधित्व किए गए फ़ाइल से बदलता है और बदली गई फ़ाइल का बैकअप बनाता है।

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | फ़ाइल को बदलने के लिए नाम |
| destinationBackupFileName | const [String](../../../system/string/)\& | बैकअप फ़ाइल का नाम |
| ignoreMetadataErrors | **bool** | यह निर्धारित करता है कि बदली गई फ़ाइल से प्रतिस्थापन फ़ाइल में मर्ज त्रुटियों को (true) होने पर अनदेखा किया जाए या (false) होने पर नहीं किया जाए |

### रिटर्न वैल्यू

एक FileInfor वस्तु जो **destinationFileName** द्वारा इंगित फ़ाइल का प्रतिनिधित्व करती है

## संबंधित देखें

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* क्लास [String](../../../system/string/)
* क्लास [FileInfo](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)