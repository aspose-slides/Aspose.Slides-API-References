---
title: FileSystemInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "FileInfo और DirectoryInfo के लिए बेस क्लास। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करने के लिए उपयोग करें।"
type: docs
weight: 300
url: /hi/system.io/filesysteminfo/
---
## FileSystemInfo क्लास


यह [FileInfo](../fileinfo/) और [DirectoryInfo](../directoryinfo/) के लिए मूल क्लास है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों को तर्क के रूप में पास करने के लिए उपयोग करें।

```cpp
class FileSystemInfo : public System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual void [Delete](./delete/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई को हटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | मान प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual void [Finalize](./finalize/)() | कुछ नहीं करता। |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई के गुण लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में लौटाता है। |
| virtual **bool** [get_Exists](./get_exists/)() | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ द्वारा संदर्भित इकाई मौजूद है या नहीं। |
| [String](../../system/string/) [get_Extension](./get_extension/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ाइल का एक्सटेंशन लौटाता है। |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का पूरा नाम (पथ सहित) लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय UTC समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय UTC समय के रूप में लौटाता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का नाम लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफरेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने की अनुमति देता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर के साथ मान प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| void [Refresh](./refresh/)() | वर्तमान ऑब्जेक्ट की स्थिति को रिफ्रेश करता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई पर निर्दिष्ट गुण सेट करता है। |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में सेट करता है। |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में सेट करता है। |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय UTC समय के रूप में सेट करता है। |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय UTC समय के रूप में सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | सभी साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)