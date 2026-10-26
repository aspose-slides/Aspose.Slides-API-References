---
title: SetLicense()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: घटक को लाइसेंस देता है।
type: docs
weight: 1
url: /hi/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) विधि


घटक को लाइसेंस देता है।

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग उपयोग करें। |
## टिप्पणी



लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. घटक असेंबली का फ़ोल्डर।

3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।

4. एंट्री असेंबली का फ़ोल्डर।

5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

**ध्यान दें:**On the .NET Compact Framework, लाइसेंस को केवल इन स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

इस उदाहरण में, MyLicense.lic नामक लाइसेंस फ़ाइल को घटक वाले फ़ोल्डर, कॉलिंग असेंबली वाले फ़ोल्डर, एंट्री असेंबली वाले फ़ोल्डर और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्स में खोजने का प्रयास किया जाएगा। 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) विधि


घटक को लाइसेंस देता है।

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लाइसेंस सम्मिलित करने वाली स्ट्रीम। |
## टिप्पणी



इस विधि का उपयोग स्ट्रीम से लाइसेंस लोड करने के लिए करें।


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ILicense](../)
* क्लास [Stream](../../../system.io/stream/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)