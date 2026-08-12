---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: C# Object.ToString() मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है।
type: docs
weight: 79
url: /hi/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const मेथड

C# [Object.ToString()](../../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है।

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### रिटर्न वैल्यू

[String](../../../system/string/) प्रतिनिधित्व जैसा कि अंतिम क्लास द्वारा प्रदान किया गया है।

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) मेथड

कलेक्शन के NameValueHeaderValue-क्लास इंस्टेंस की स्ट्रिंग प्रतिनिधित्व लौटाता है।

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-क्लास इंस्टेंस का कलेक्शन। |
| separator | char16_t | एक स्ट्रिंग सेपरेटर। |
| leadingSeparator | **bool** | वह मान जो दर्शाता है कि क्या पहले कलेक्शन आइटम से पहले स्ट्रिंग सेपरेटर जोड़ना आवश्यक है। |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | एक इंस्टेंस जहाँ स्ट्रिंग प्रतिनिधित्व असाइन किया जाएगा। |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) मेथड

NameValueHeaderValue-क्लास इंस्टेंस के कलेक्शन की स्ट्रिंग प्रतिनिधित्व लौटाता है।

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-क्लास इंस्टेंस का कलेक्शन। |
| separator | char16_t | एक स्ट्रिंग सेपरेटर। |
| leadingSeparator | **bool** | वह मान जो दर्शाता है कि क्या पहले कलेक्शन आइटम से पहले स्ट्रिंग सेपरेटर जोड़ना आवश्यक है। |

### रिटर्न वैल्यू

NameValueHeaderValue-क्लास इंस्टेंस के कलेक्शन की स्ट्रिंग प्रतिनिधित्व।

## सम्बंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [NameValueHeaderValue](../)
* क्लास [ObjectCollection](../../objectcollection/)
* क्लास [StringBuilder](../../../system.text/stringbuilder/)
* नामस्थान [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)