---
title: OperatingSystem
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक विशिष्ट ऑपरेटिंग सिस्टम को दर्शाता है और उसके बारे में जानकारी प्रदान करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या ऐसर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 1171
url: /hi/system/operatingsystem/
---
## OperatingSystem क्लास

विशिष्ट ऑपरेटिंग सिस्टम को दर्शाता है और इसके बारे में जानकारी प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या अभिकथन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।

```cpp
class OperatingSystem
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | वर्तमान वस्तु द्वारा दर्शाए गए ऑपरेटिंग सिस्टम का प्लेटफ़ॉर्म पहचानकर्ता लौटाता है। |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | वर्तमान वस्तु द्वारा दर्शाए गए ऑपरेटिंग सिस्टम के सर्विस पैक नाम को लौटाता है। |
| const [Version](../version/)\& [get_Version](./get_version/)() const | वर्तमान वस्तु द्वारा दर्शाए गए ऑपरेटिंग सिस्टम के संस्करण को दर्शाने वाले [Version](../version/) वस्तु का स्थिर संदर्भ लौटाता है। |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | वर्तमान वस्तु द्वारा दर्शाए गए ऑपरेटिंग सिस्टम के संस्करण की स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static **bool** [IsFreeBSD](./isfreebsd/)() | यह दर्शाता है कि वर्तमान एप्लिकेशन FreeBSD पर चल रहा है या नहीं। |
| static **bool** [IsLinux](./islinux/)() | यह दर्शाता है कि वर्तमान एप्लिकेशन Linux पर चल रहा है या नहीं। |
| static **bool** [IsMacOS](./ismacos/)() | यह दर्शाता है कि वर्तमान एप्लिकेशन MacOS पर चल रहा है या नहीं। |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | यह दर्शाता है कि वर्तमान एप्लिकेशन निर्दिष्ट प्लेटफ़ॉर्म पर चल रहा है या नहीं। |
| static **bool** [IsWindows](./iswindows/)() | यह दर्शाता है कि वर्तमान एप्लिकेशन [Windows](../../system.windows/) पर चल रहा है या नहीं। |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | एक उदाहरण बनाता है जो एक विशिष्ट प्लेटफ़ॉर्म आईडी और संस्करण के रूप में निर्दिष्ट ऑपरेटिंग सिस्टम को दर्शाता है। |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | एक उदाहरण बनाता है जो एक विशिष्ट प्लेटफ़ॉर्म आईडी, संस्करण और सर्विस पैक के रूप में निर्दिष्ट ऑपरेटिंग सिस्टम को दर्शाता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान वस्तु द्वारा दर्शाए गए ऑपरेटिंग सिस्टम के संस्करण की स्ट्रिंग प्रतिनिधित्व लौटाता है। |

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)