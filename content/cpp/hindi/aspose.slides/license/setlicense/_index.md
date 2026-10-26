---
title: SetLicense()
second_title: Aspose.Slides for C++ API संदर्भ
description: घटक को लाइसेंस प्रदान करता है।
type: docs
weight: 14
url: /hi/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) मेथड

घटक को लाइसेंस प्रदान करता है।

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | पूर्ण या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |

## टिप्पणी

लाइसेंस को निम्नलिखित स्थानों पर खोजने का प्रयास करता है:

1. स्पष्ट पथ।
2. घटक असेंबली का फ़ोल्डर।
3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।
4. एंट्री असेंबली का फ़ोल्डर।
5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

**नोट:** .NET Compact Framework में, लाइसेंस को केवल इन स्थानों पर खोजता है:

1. स्पष्ट पथ।
2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर और फिर कॉलिंग असेंब्ली के एम्बेडेड रिसोर्स में MyLicense.lic नाम की लाइसेंस फ़ाइल को खोजने का प्रयास किया जाएगा। 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) मेथड

घटक को लाइसेंस प्रदान करता है।

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

## टिप्पणी

इस मेथड का उपयोग स्ट्रीम से लाइसेंस लोड करने के लिए करें।

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [License](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)