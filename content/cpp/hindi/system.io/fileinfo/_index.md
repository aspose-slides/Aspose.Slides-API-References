---
title: FileInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "फ़ाइल के पथ और इस पथ द्वारा संदर्भित फ़ाइल का प्रतिनिधित्व करता है तथा इसे व्यवस्थित करने के लिए विधियाँ प्रदान करता है। इस क्लास की वस्तुएँ केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन के तर्क के रूप में पास करने के लिये करें।"
type: docs
weight: 274
url: /hi/system.io/fileinfo/
---
## FileInfo क्लास

Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को UTF-8 एन्कोडिंग के साथ टेक्स्ट लिखने हेतु खोलता है, 'Append' मोड में और बिना शेयरिंग के। |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि गंतव्य फ़ाइल पहले से मौजूद है, तो कॉपी विफल हो जाता है। |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। एक पैरामीटर यह निर्धारित करता है कि मौजूदा गंतव्य फ़ाइल को अधिलेखित किया जाना चाहिए या नहीं। |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए पथ द्वारा निर्दिष्ट स्थान पर फ़ाइल बनाता है और उसे पढ़ने और लिखने के लिए खोलता है, truncate मोड में और बिना शेयरिंग के। |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए पथ द्वारा निर्दिष्ट स्थान पर फ़ाइल बनाता है और उसे UTF-8 एन्कोडिंग के साथ टेक्स्ट लिखने के लिये बिना शेयरिंग के खोलता है। |
| void [Decrypt](./decrypt/)() | लागू नहीं किया गया। |
| void [Delete](./delete/)() override | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को हटाता है। |
| void [Encrypt](./encrypt/)() | लागू नहीं किया गया। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल का प्रतिनिधित्व करने वाले [FileInfo](./) क्लास की नई इंस्टेंस बनाता है। |
| virtual void [Finalize](../filesysteminfo/finalize/)() | कुछ नहीं करता। |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई के गुणों को लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में लौटाता है। |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | [DirectoryInfo](../directoryinfo/) वस्तु को लौटाता है जो उस डायरेक्टरी का प्रतिनिधित्व करता है जिसमें वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल स्थित है। |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल स्थित डायरेक्टरी का पूर्ण नाम लौटाता है। |
| **bool** [get_Exists](./get_exists/)() override | फ़ाइल के अस्तित्व को दर्शाने वाला मान लौटाता है। |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल का एक्सटेंशन लौटाता है। |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का पूर्ण नाम (पथ सहित) लौटाता है। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | ReadOnly गुण सेट है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम अभिगमन समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम अभिगमन समय UTC समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय स्थानीय समय के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय UTC समय के रूप में लौटाता है। |
| **int64_t** [get_Length](./get_length/)() | फ़ाइल का आकार बाइट्स में लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | फ़ाइल का नाम लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से सम्बंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु की वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को निर्दिष्ट स्थान पर ले जाता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | निर्दिष्ट मोड में, पढ़ने और लिखने के लिए, और बिना शेयरिंग के वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को खोलता है। |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | निर्दिष्ट मोड, निर्दिष्ट एक्सेस प्रकार, और बिना शेयरिंग के वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को खोलता है। |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | निर्दिष्ट मोड, निर्दिष्ट एक्सेस प्रकार, और शेयरिंग विकल्प के साथ वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को खोलता है। |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | केवल पढ़ने के लिए, 'Open' मोड में, पढ़ने के लिये साझा एक्सेस के साथ वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को खोलता है। |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए पथ द्वारा निर्दिष्ट स्थान पर मौजूद फ़ाइल को UTF-8 एन्कोडिंग के साथ टेक्स्ट पढ़ने हेतु बिना शेयरिंग के खोलता है। |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | केवल लिखने के लिए, 'OpenOrCreate' मोड में, बिना शेयरिंग के वर्तमान वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल को खोलता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के द्वारा वैल्यू टाइप वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| void [Refresh](../filesysteminfo/refresh/)() | वर्तमान वस्तु की स्थिति को पुनः ताज़ा करता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट गंतव्य फ़ाइल की सामग्री को वर्तमान [FileInfo](./) वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल से बदलता है और प्रतिस्थापित फ़ाइल का बैकअप बनाता है। |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | निर्दिष्ट गंतव्य फ़ाइल की सामग्री को वर्तमान [FileInfo](./) वस्तु द्वारा प्रतिनिधित्व की गई फ़ाइल से बदलता है और प्रतिस्थापित फ़ाइल का बैकअप बनाता है। |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई पर निर्दिष्ट गुण सेट करता है। |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय स्थानीय समय के रूप में सेट करता है। |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का निर्माण समय UTC समय के रूप में सेट करता है। |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | फ़ाइल पर ReadOnly गुण को सेट या अनसेट करता है। |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम अभिगमन समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम अभिगमन समय UTC समय के रूप में सेट करता है। |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय स्थानीय समय के रूप में सेट करता है। |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए इकाई का अंतिम लेखन समय UTC समय के रूप में सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए पथ को लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [FileSystemInfo](../filesysteminfo/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)