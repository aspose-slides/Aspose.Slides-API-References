---
title: ToUpper()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट वर्ण को बड़े अक्षर में परिवर्तित करता है।
type: docs
weight: 222
url: /hi/system/char/toupper/
---
## Char::ToUpper(char_t) विधि

निर्दिष्ट वर्ण को बड़े अक्षर में परिवर्तित करता है।

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | परिवर्तित करने हेतु वर्ण |

### Return Value

यदि निर्दिष्ट वर्ण लोअर केस अक्षर है तो वह अपर केस में परिवर्तित हो जाता है, अन्यथा - वही वर्ण

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) विधि

निर्दिष्ट वर्ण को बड़े अक्षर में परिवर्तित करता है।

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | परिवर्तित करने हेतु वर्ण |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | एक ऑब्जेक्ट जो संस्कृति-विशिष्ट केसिंग नियम प्रदान करता है। |

### Return Value

यदि निर्दिष्ट वर्ण लोअर केस अक्षर है तो वह अपर केस में परिवर्तित हो जाता है, अन्यथा - वही वर्ण

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Char](../)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)