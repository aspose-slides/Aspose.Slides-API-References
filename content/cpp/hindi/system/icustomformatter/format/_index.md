---
title: Format()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की स्ट्रिंग प्रस्तुति निर्दिष्ट फ़ॉर्मेट का उपयोग करके लौटाता है।
type: docs
weight: 1
url: /hi/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की स्ट्रिंग प्रस्तुति निर्दिष्ट फ़ॉर्मेट का उपयोग करके लौटाता है।

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| format | [System::String](../../string/) | स्ट्रिंग फ़ॉर्मेट |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | फ़ॉर्मेट करने हेतु ऑब्जेक्ट |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | फ़ॉर्मेटिंग जानकारी प्रदान करने वाला ऑब्जेक्ट |

### रिटर्न मान

**arg** को **format** और **formatProvider** द्वारा निर्दिष्ट फ़ॉर्मेट के अनुसार फ़ॉर्मेट किया गया स्ट्रिंग प्रतिनिधित्व।

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Object](../../object/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [ICustomFormatter](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)