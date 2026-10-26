---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट एट्रिब्यूट के मानों को सत्यापित करता है और सेट करता है।
type: docs
weight: 482
url: /hi/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) विधि

डिफ़ॉल्ट एट्रिब्यूट के मानों को सत्यापित करता है और सेट करता है।

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | कुकी की विशिष्टता। |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Uri-क्लास का उदाहरण जो आंतरिक फ़ील्ड्स को प्रारम्भ करने के लिए उपयोग किया जाता है। |
| isLocalDomain | **bool** | एक मान जो दर्शाता है कि कुकी को स्थानीय डोमेन में पुश किया गया है या नहीं। |
| localDomain | [String](../../../system/string/) | एक स्थानीय डोमेन नाम। |
| setDefault | **bool** | एक मान जो दर्शाता है कि कुकी के एट्रिब्यूट को उनके डिफ़ॉल्ट मानों से प्रारम्भ किया जाना चाहिए। |
| shouldThrow | **bool** | एक मान जो दर्शाता है कि निर्दिष्ट मान अवैध होने पर अपवाद फेंका जाना चाहिए। |

### रिटर्न मान

सभी मान मान्य होने पर true, अन्यथा false।

## अन्य देखें

* एन्युम [CookieVariant](../../cookievariant/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [Cookie](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)