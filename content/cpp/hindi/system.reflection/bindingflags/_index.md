---
title: BindingFlags
second_title: Aspose.Slides for C++ API संदर्भ
description: सदस्यों और प्रकारों की खोज मोड और बाइंडिंग को परिभाषित करता है।
type: docs
weight: 157
url: /hi/system.reflection/bindingflags/
---
## BindingFlags enum

सदस्यों और प्रकारों की खोज मोड और बाइंडिंग को परिभाषित करता है।

```cpp
enum class BindingFlags
```

### मान

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | कोई विशेष विकल्प नहीं। |
| IgnoreCase | 1 | आइटेम खोजते समय नाम के केस को अनदेखा करें। |
| DeclaredOnly | 2 | केवल उन सदस्यों को देखें जो प्रकार में घोषित किए गए हैं और बेसटाइप में नहीं। |
| Instance | 4 | इंस्टेंस सदस्यों को देखें। |
| Static | 8 | स्टेटिक सदस्यों को देखें। |
| Public | 16 | पब्लिक सदस्यों को देखें। |
| NonPublic | 32 | गैर-पब्लिक सदस्यों को देखें। |
| FlattenHierarchy | 64 | बेसटाइप के पब्लिक और प्रोटेक्टेड स्टेटिक सदस्यों को देखें। |
| InvokeMethod | 256 | मेथड को कॉल करता है। |
| CreateInstance | 512 | रिफ्लेक्टेड प्रकार का इंस्टेंस बनाता है। |
| GetField | 1024 | फ़ील्ड का मान प्राप्त करता है। |
| SetField | 2048 | फ़ील्ड का मान सेट करता है। |
| GetProperty | 4096 | प्रॉपर्टी का मान प्राप्त करता है। |
| SetProperty | 8192 | प्रॉपर्टी का मान सेट करता है। |
| PutDispProperty | 16384 | COM प्रॉपर्टी सेट करता है। |
| PutRefDispProperty | 32768 | COM रेफ़रेंस प्रॉपर्टी सेट करता है। |
| ExactBinding | 65536 | टाइप बाइंडिंग बिल्कुल सटीक होना चाहिए, बिना किसी टाइप परिवर्तन के। |
| SuppressChangeType | 131072 | समर्थित नहीं है। |
| OptionalParamBinding | 262144 | आर्ग्यूमेंट्स की संख्या के आधार पर ओवरलोड चुनता है। |
| IgnoreReturn | 16777216 | COM इंटरऑप रिटर्न वैल्यू को अनदेखा करता है। |

## देखें

* नामस्थान [System::Reflection](../)
* लाइब्रेरी [Aspose.Slides](../../)