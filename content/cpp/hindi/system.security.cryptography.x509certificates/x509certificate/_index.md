---
title: X509Certificate
second_title: "Aspose.Slides C++ के लिए API रेफ़रेंस"
description: "X.509 v.3 प्रमाणपत्र। एन्क्रिप्टेड प्रमाणपत्र समर्थित नहीं हैं। केवल X509KeyStorageFlags::DefaultKeySet फ़्लैग समर्थित है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन दोषों का कारण बनेगा। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 27
url: /hi/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate क्लास


X.509 v.3 प्रमाणपत्र। एन्क्रिप्टेड प्रमाणपत्र समर्थित नहीं हैं। केवल [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) फ़्लैग समर्थित है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी नहीं बनाना चाहिए, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स को आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | निर्दिष्ट PKCS7 फ़ाइल से प्रमाणपत्र बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | निर्दिष्ट हस्ताक्षरित फ़ाइल से प्रमाणपत्र बनाता है। |
| void [Dispose](./dispose/)() override | कुछ नहीं करता। |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | दो प्रमाणपत्रों की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप वस्तुओं की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं किया गया। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं किया गया। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं किया गया। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| IntPtr [get_Handle](./get_handle/)() const | Microsoft Cryptographic API प्रमाणपत्र संदर्भ के लिए हैंडल प्राप्त करता है। |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | X.509v3 प्रमाणपत्र जारी करने वाले प्रमाणपत्र प्राधिकारी का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | प्रमाणपत्र से सब्जेक्ट डिस्टिंग्विश्ड नाम प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | वर्तमान ऑब्जेक्ट के लिए हैश बाइट एरे के रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | वर्तमान ऑब्जेक्ट के लिए हैश बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | वर्तमान ऑब्जेक्ट के लिए [SHA1](../../system.security.cryptography/sha1/) हैश को हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | वर्तमान ऑब्जेक्ट के लिए [SHA1](../../system.security.cryptography/sha1/) हैश को हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | वर्तमान प्रमाणपत्र की प्रभावी तिथि प्राप्त करता है। |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | वर्तमान प्रमाणपत्र की समाप्ति तिथि प्राप्त करता है। |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | प्रमाणपत्र फ़ॉर्मेट का नाम प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | प्रमाणपत्र हैश कोड प्राप्त करता है। |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | वर्तमान प्रमाणपत्र जारी करने वाले प्रमाणन प्राधिकरण का नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी स्ट्रिंग रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी बाइट एरे रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी हेक्साडेसिमल स्ट्रिंग रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetName](./getname/)() const | वर्तमान प्रमाणपत्र जारी किए गए प्रिंसिपल का नाम प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | प्रमाणपत्र से सार्वजनिक कुंजी बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | प्रमाणपत्र से सार्वजनिक कुंजी को हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | प्रमाणपत्र से रॉ डेटा बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | प्रमाणपत्र से रॉ डेटा को हेक्साडेसिमल स्ट्रिंग रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | प्रमाणपत्र से सीरियल नंबर बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | प्रमाणपत्र से सीरियल नंबर को हेक्साडेसिमल स्ट्रिंग रूप में प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। लागू नहीं किया गया। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | एसेनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | निल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और निल पॉइंटर केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउण्ट घटाता है। |
| virtual void [Reset](./reset/)() | प्रमाणपत्र की स्थिति रीसेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउण्ट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउण्ट को घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | टेक्स्ट फ़ॉर्मेट में प्रमाणपत्र सूचना लौटाता है। |
| [String](../../system/string/) [ToString](./tostring/)() const override | टेक्स्ट फ़ॉर्मेट में प्रमाणपत्र सूचना लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउण्ट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउण्ट को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कन्स्ट्रक्टर। |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कन्स्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | पॉइंटर प्रकार। |
## देखें

* क्लास [Object](../../system/object/)
* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [System::Security::Cryptography::X509Certificates](../)
* लाइब्रेरी [Aspose.Slides](../../)