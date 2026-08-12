---
title: ECDsaBotan
second_title: Aspose.Slides for C++ API संदर्भ
description: "Botan रूप में ECDsa एल्गोरिद्म। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या आश्वासन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 196
url: /hi/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan वर्ग


[ECDsa](../ecdsa/) एल्गोरिद्म Botan रूप में। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या आश्वासन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन के तर्क के रूप में पास करें।

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## विधियां

| विधि | विवरण |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | सभी संसाधनों को रिलीज़ करता है। |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)() | डिफ़ॉल्ट ECDSA एल्गोरिद्म कार्यान्वयन बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECCurve](../eccurve/)\&) | निर्दिष्ट वक्र पर नवीनतम निर्मित कुंजी के साथ डिफ़ॉल्ट ECDSA एल्गोरिद्म कार्यान्वयन बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECParameters](../ecparameters/)\&) | निर्दिष्ट पैरामीटरों का उपयोग करके डिफ़ॉल्ट ECDSA एल्गोरिद्म कार्यान्वयन बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [String](../../system/string/)\&) | निर्दिष्ट ECDSA एल्गोरिद्म कार्यान्वयन बनाता है। |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा स्वामित्व वाले संसाधनों को रिलीज़ करता है। |
|  [ECDsaBotan](./ecdsabotan/)() | कंस्ट्रक्टर। डिफ़ॉल्ट पैरामीटरों का उपयोग करता है। |
|  [ECDsaBotan](./ecdsabotan/)(const [ECParameters](../ecparameters/)\&) | कंस्ट्रक्टर। |
|  [ECDsaBotan](./ecdsabotan/)(const [ECCurve](../eccurve/)\&) | कंस्ट्रक्टर। |
|  [ECDsaBotan](./ecdsabotan/)(**int32_t**) | कंस्ट्रक्टर। |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | कंस्ट्रक्टर। |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | कंस्ट्रक्टर। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) override | स्पष्ट पैरामीटर निर्यात करता है। |
| [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) override | नामांकित या स्पष्ट पैरामीटर निर्यात करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | XML-एन्कोडेड पैरामीटरों का उपयोग करके वस्तु को प्रारंभ करता है। लागू नहीं किया गया। |
| void [FromXmlString](./fromxmlstring/)(const [String](../../system/string/)\&, [ECKeyXmlFormat](../eckeyxmlformat/)) | XML-एन्कोडेड पैरामीटरों का उपयोग करके वस्तु को प्रारंभ करता है। लागू नहीं किया गया। |
| void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) override | निर्दिष्ट वक्र के लिए नया सार्वजनिक/निजी कुंजी जोड़ी उत्पन्न करता है। |
| [HashAlgorithmName](../hashalgorithmname/) [get_HashAlgorithm](./get_hashalgorithm/)() const | हैश एल्गोरिद्म प्राप्त करता है। |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](../ecdsa/get_keyexchangealgorithm/)() override | उपयोग करने के लिए कुंजी विनिमय एल्गोरिद्म प्राप्त करता है। |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | कुंजी आकार प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | अनुमत कुंजी आकारों की श्रृंखला प्राप्त करता है। |
| [String](../../system/string/) [get_SignatureAlgorithm](../ecdsa/get_signaturealgorithm/)() override | उपयोग करने के लिए हस्ताक्षर एल्गोरिद्म प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([ByteArrayPtr](../../system/bytearrayptr/), **int32_t**, **int32_t**, [HashAlgorithmName](../hashalgorithmname/)) override | निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट डेटा सरणी का हैश मान गणना करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([StreamPtr](../../system/streamptr/), [HashAlgorithmName](../hashalgorithmname/)) override | निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट बाइनरी स्ट्रीम का हैश मान गणना करता है। |
| void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) override | डेटा स्ट्रक्चर से सभी पैरामीटर आयात करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु लक्ष्य प्रकार द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन लॉकिंग को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की वस्तु की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_HashAlgorithm](./set_hashalgorithm/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | हैश एल्गोरिद्म सेट करता है। |
| void [set_KeySize](./set_keysize/)(**int32_t**) override | कुंजी आकार सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्पलेट तर्क को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | निर्दिष्ट डेटा सरणी का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | निर्दिष्ट डेटा सरणी का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&) | निर्दिष्ट बाइनरी स्ट्रीम का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | निर्दिष्ट डेटा सरणी का हैश मान निर्दिष्ट हैश एल्गोरिद्म से गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | निर्दिष्ट डेटा सरणी का हैश मान निर्दिष्ट हैश एल्गोरिद्म से गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | निर्दिष्ट बाइनरी स्ट्रीम का हैश मान निर्दिष्ट हैश एल्गोरिद्म से गणना करता है और परिणाम पर हस्ताक्षर करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | सभी पैरामीटर को XML स्वरूप में निर्यात करता है। लागू नहीं किया गया। |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)([ECKeyXmlFormat](../eckeyxmlformat/)) | सभी पैरामीटर को XML स्वरूप में निर्यात करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) अभिव्यक्ति को कार्यान्वित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन अनलॉकिंग को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट का उपयोग करें। |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | verifies that the signature of the specified data is valid. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | verifies that the signature of the specified data is valid. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | verifies that the signature of the specified binary stream is valid. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | verifies that the signature of the specified data is valid. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | verifies that the signature of the specified data is valid. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | verifies that the signature of the specified binary stream is valid. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | डेटा हस्ताक्षर की जांच करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## संबंधित देखें

* Class [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)