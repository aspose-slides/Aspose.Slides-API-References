---
title: X509Certificate2
second_title: Aspose.Slides for C++ API संदर्भ
description: "X509 प्रमाणपत्र का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही अलोकित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 40
url: /hi/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 क्लास

X509 प्रमाणपत्र का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही अलोकित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिये करें।

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | निर्दिष्ट PKCS7 फ़ाइल से प्रमाणपत्र बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | निर्दिष्ट साइन किए गए फ़ाइल से प्रमाणपत्र बनाता है। |
| void [Dispose](../x509certificate/dispose/)() override | कुछ भी नहीं करता। |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | दो प्रमाणपत्रों की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | दो NaN मानों को समान मानते हुए C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | दो NaN मानों को समान मानते हुए C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | निर्दिष्ट फॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में एक्सपोर्ट करता है। लागू नहीं किया गया। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | निर्दिष्ट फॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में एक्सपोर्ट करता है। लागू नहीं किया गया। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | निर्दिष्ट फॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में एक्सपोर्ट करता है। लागू नहीं किया गया। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिये। |
| **bool** [get_Archived](./get_archived/)() const | एक मान प्राप्त करता है जो दर्शाता है कि प्रमाणपत्र संग्रहित है। |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | प्रमाणपत्र से जुड़े विस्तारित ऑब्जेक्ट्स का संग्रह प्राप्त करता है। |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | प्रमाणपत्र का फ्रेंडली नाम प्राप्त करता है। |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Microsoft Cryptographic API प्रमाणपत्र कॉन्टेक्स्ट का हैंडल प्राप्त करता है। |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | जाँचता है कि प्रमाणपत्र में निजी कुंजी है या नहीं। |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | X.509v3 प्रमाणपत्र जारी करने वाली प्रमाणपत्र प्राधिकरण का नाम प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | प्रमाणपत्र जारी करने वाले पक्ष का नाम प्राप्त करता है। |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | स्थानीय तिथि और समय प्राप्त करता है जिसके बाद प्रमाणपत्र वैध नहीं रहता। |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | स्थानीय तिथि और समय प्राप्त करता है जिस पर प्रमाणपत्र वैध हो जाता है। |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | प्रमाणपत्र से जुड़ी निजी कुंजी प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | एक प्रमाणपत्र [PublicKey](../publickey/) ऑब्जेक्ट प्राप्त करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | प्रमाणपत्र का कच्चा डेटा प्राप्त करता है। |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | प्रमाणपत्र का सीरियल नंबर प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | प्रमाणपत्र के हस्ताक्षर बनाने के लिये उपयोग किया गया एल्गोरिथ्म प्राप्त करता है। |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | प्रमाणपत्र से विषय का विशिष्ट नाम प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | प्रमाणपत्र से विषय नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | प्रमाणपत्र का थम्बप्रिंट प्राप्त करता है। |
| **int32_t** [get_Version](./get_version/)() const | प्रमाणपत्र फॉर्मेट संस्करण प्राप्त करता है। |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | निर्दिष्ट बाइट एरे में मौजूद प्रमाणपत्र के प्रकार को प्राप्त करता है। |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल में मौजूद प्रमाणपत्र के प्रकार को प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | वर्तमान ऑब्जेक्ट के हैश को बाइट एरे के रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | वर्तमान ऑब्जेक्ट के हैश को बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | [SHA1](../../system.security.cryptography/sha1/) हैश को हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | [SHA1](../../system.security.cryptography/sha1/) हैश को हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | [RSA](../../system.security.cryptography/rsa/) निजी कुंजी प्राप्त करता है; |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | [RSA](../../system.security.cryptography/rsa/) सार्वजनिक कुंजी प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | [RSA](../../system.security.cryptography/rsa/) निजी कुंजी प्राप्त करता है; |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | [RSA](../../system.security.cryptography/rsa/) सार्वजनिक कुंजी प्राप्त करता है। |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | वर्तमान प्रमाणपत्र की प्रभावी तिथि प्राप्त करता है। |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | वर्तमान प्रमाणपत्र की समाप्ति तिथि प्राप्त करता है। |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | प्रमाणपत्र फॉर्मेट का नाम प्राप्त करता है। |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | प्रमाणपत्र का हैश कोड प्राप्त करता है। |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | वर्तमान प्रमाणपत्र जारी करने वाले प्रमाणपत्र प्राधिकरण का नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | वर्तमान प्रमाणपत्र के लिए कुंजी जानकारी हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | वर्तमान प्रमाणपत्र जारी किए जाने वाले प्रमुख का नाम प्राप्त करता है। |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | प्रमाणपत्र से विषय या जारीकर्ता नाम प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | प्रमाणपत्र से सार्वजनिक कुंजी बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | प्रमाणपत्र से सार्वजनिक कुंजी हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | प्रमाणपत्र से कच्चा डेटा बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | प्रमाणपत्र से कच्चा डेटा हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | [RSA](../../system.security.cryptography/rsa/) निजी कुंजी प्राप्त करता है; |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | [RSA](../../system.security.cryptography/rsa/) सार्वजनिक कुंजी प्राप्त करता है। |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | प्रमाणपत्र से सीरियल नंबर बाइट एरे के रूप में प्राप्त करता है। |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | प्रमाणपत्र से सीरियल नंबर हेक्साडेसिमल स्ट्रिंग के रूप में प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानान्तर। |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। |
| void [Import](./import/)(const [String](../../system/string/)\&) override | निर्दिष्ट प्रमाणपत्र फ़ाइल से जानकारी आयात करता है। |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | निर्दिष्ट प्रमाणपत्र डेटा से जानकारी आयात करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानान्तर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानान्तर। कस्टम टाइप्स को क्लोन करने की अनुमति देता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा मान प्रकार के ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस हेतु विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस हेतु विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Reset](./reset/)() override | प्रमाणपत्र की स्थिति को रीसेट करता है। |
| void [set_Archived](./set_archived/)(**bool**) const | एक मान सेट करता है जो दर्शाता है कि प्रमाणपत्र संग्रहित है। |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | प्रमाणपत्र का फ्रेंडली नाम सेट करता है। |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | प्रमाणपत्र से जुड़ी निजी कुंजी को सेट या साफ़ करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेर्ड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीकर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके स्थान पर स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | टेक्स्ट फॉर्मेट में प्रमाणपत्र जानकारी लौटाता है। |
| [String](../../system/string/) [ToString](./tostring/)() const override | टेक्स्ट फॉर्मेट में प्रमाणपत्र जानकारी लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| **bool** [Verify](./verify/)() const | प्रमाणपत्र श्रृंखला को सत्यापित करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके स्थान पर स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|   [X509Certificate](../x509certificate/x509certificate/)() | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)() | खाली [X509Certificate2](./) बनाता है। |
|   [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
|   [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | कंस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [X509Certificate](../x509certificate/)
* नामस्थान [System::Security::Cryptography::X509Certificates](../)
* लाइब्रेरी [Aspose.Slides](../../)