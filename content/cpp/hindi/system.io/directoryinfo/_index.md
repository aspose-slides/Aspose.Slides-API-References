---
title: DirectoryInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "फ़ाइल सिस्टम पथ, इस पथ द्वारा संदर्भित एक डायरेक्टरी का प्रतिनिधित्व करता है और डायरेक्टरीज़ को संशोधित करने के लिए इंस्टेंस मेथड्स प्रदान करता है। इस वर्ग के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही एलोकेट किया जाना चाहिए। इस प्रकार को स्टैक पर या operator new का उपयोग करके कभी भी इंस्टेंस न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या एसेर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 248
url: /hi/system.io/directoryinfo/
---
## DirectoryInfo वर्ग

फ़ाइल सिस्टम पथ का प्रतिनिधित्व करता है, इस पथ द्वारा निर्दिष्ट डायरेक्टरी और डायरेक्टरी को संशोधित करने के लिए इंस्टेंस मेथड्स प्रदान करता है। इस वर्ग के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही एलोकेट किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या एसेर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन्स में तर्क के रूप में पास करें।

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Create](./create/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ पर एक डायरेक्टरी बनाता है। |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ पर उपडायरेक्टरी बनाता है। |
| void [Delete](./delete/)() override | यदि डायरेक्टरी खाली है, तो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ द्वारा निर्दिष्ट डायरेक्टरी को हटा देती है। |
| void [Delete](./delete/)(**bool**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ द्वारा निर्दिष्ट डायरेक्टरी को हटाता है। एक पैरामीटर यह निर्धारित करता है कि यदि डायरेक्टरी खाली नहीं है तो उसकी सामग्री को पुनरावर्ती रूप से हटाया जाए। |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ पर [DirectoryInfo](./) वर्ग की एक इंस्टेंस बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी डायरेक्टरीज़ को शामिल करने वाला इटेरेबल संग्रह लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली डायरेक्टरीज़ की खोज करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली डायरेक्टरीज़ की खोज करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी फ़ाइलों को शामिल करने वाला इटेरेबल संग्रह लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों की खोज करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों की खोज करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी फ़ाइलों और डायरेक्टरीज़ को शामिल करने वाला इटेरेबल संग्रह लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual void [Finalize](../filesysteminfo/finalize/)() | कुछ नहीं करता। |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई के गुणधर्म लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में लौटाता है। |
| **bool** [get_Exists](./get_exists/)() override | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया पथ मौज़ूद डायरेक्टरी को दर्शाता है या नहीं। |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ाइल का एक्सटेंशन लौटाता है। |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का पूर्ण नाम (पथ सहित) लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय UTC समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लिखने का समय UTC समय के रूप में लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ द्वारा संदर्भित इकाई का नाम लौटाता है। |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई डायरेक्टरी के पैरेंट डायरेक्टरी को संदर्भित करने वाले पथ का प्रतिनिधित्व करने वाले [DirectoryInfo](./) ऑब्जेक्ट के लिए एक साझा पॉइंटर लौटाता है। |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई डायरेक्टरी के रूट डायरेक्टरी को संदर्भित करने वाले पथ का प्रतिनिधित्व करने वाले [DirectoryInfo](./) ऑब्जेक्ट के लिए एक साझा पॉइंटर लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबन्धित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी डायरेक्टरीज़ का प्रतिनिधित्व करने वाले [DirectoryInfo](./) ऑब्जेक्ट्स के साझा पॉइंटरों को सम्मिलित करने वाला एक एरे लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली डायरेक्टरीज़ की खोज करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली डायरेक्टरीज़ की खोज करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी डायरेक्टरीज़ का प्रतिनिधित्व करने वाले [FileInfo](../fileinfo/) ऑब्जेक्ट्स के साझा पॉइंटरों को सम्मिलित करने वाला एक एरे लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों की खोज करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों की खोज करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में स्थित सभी फ़ाइलों और डायरेक्टरीज़ का प्रतिनिधित्व करने वाले [FileSystemInfo](../filesysteminfo/) ऑब्जेक्ट्स के साझा पॉइंटरों को सम्मिलित करने वाला एक एरे लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए डायरेक्टरी में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी या उसी से मूल डायरेक्टरी ट्री में निर्दिष्ट खोज मानदंडों को पूरा करने वाली फ़ाइलों और डायरेक्टरीज़ की खोज करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स के क्लोनिंग को सक्षम करता है। |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गई डायरेक्टरी और उसकी सभी सामग्री को निर्दिष्ट स्थान पर ले जाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नलपॉइंटर के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| void [Refresh](../filesysteminfo/refresh/)() | वर्तमान ऑब्जेक्ट की स्थिति को रिफ्रेश करता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई पर निर्दिष्ट गुणधर्म सेट करता है। |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में सेट करता है। |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में सेट करता है। |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम एक्सेस समय UTC समय के रूप में सेट करता है। |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लिखने का समय UTC समय के रूप में सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पथ को शामिल करने वाला स्ट्रिंग लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [FileSystemInfo](../filesysteminfo/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)