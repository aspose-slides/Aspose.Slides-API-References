---
title: Uri
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एकीकृत संसाधन पहचानकर्ता। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही बनाया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां या एसेर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 1392
url: /hi/system/uri/
---
## Uri वर्ग

Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | निर्दिष्ट होस्ट नाम का प्रकार निर्धारित करता है। |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | निर्दिष्ट स्कीम वैध है या नहीं निर्धारित करता है। |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | निर्दिष्ट [Uri](./) वस्तुओं की तुलना निर्दिष्ट तुलना नियमों का उपयोग करके करता है। |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए URI समान हैं या नहीं निर्धारित करता है। |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | वस्तुओं की तुलना C# [Object.Equals](../object/equals/) अर्थविन्यास का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार की वस्तुओं की तुलना C# शैली में करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | एक स्ट्रिंग को उसके एस्केप्ड प्रतिनिधित्व में परिवर्तित करता है। |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | एक URI स्ट्रिंग को उसके एस्केप्ड प्रतिनिधित्व में परिवर्तित करता है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | एक हेक्साडेसिमल अंक का दशमलव मान प्राप्त करता है। |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | URI का निरपेक्ष पथ लौटाता है। |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | निरपेक्ष URI लौटाता है। |
| [String](../string/) [get_Authority](./get_authority/)() const | सर्वर के लिए होस्ट नाम और पोर्ट नंबर लौटाता है। |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | एक अनएस्केप्ड होस्ट नाम लौटाता है। |
| [String](../string/) [get_Fragment](./get_fragment/)() const | एस्केप्ड URI फ्रैगमेंट लौटाता है। |
| [String](../string/) [get_Host](./get_host/)() const | होस्ट नाम लौटाता है। |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | होस्ट नाम प्रकार लौटाता है। |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | होस्ट का अंतरराष्ट्रीय डोमेन नाम लौटाता है। |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया URI निरपेक्ष है या नहीं। |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया URI उसकी स्कीम के लिए डिफ़ॉल्ट पोर्ट रखता है या नहीं। |
| **bool** [get_IsFile](./get_isfile/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया URI फ़ाइल है या नहीं। |
| **bool** [get_IsLoopback](./get_isloopback/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया URI स्थानीय होस्ट को संदर्भित करता है या नहीं। |
| **bool** [get_IsUnc](./get_isunc/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया URI UNC पथ है या नहीं। |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI द्वारा संदर्भित फ़ाइल नाम का ऑपरेटिंग सिस्टम प्रतिनिधित्व लौटाता है। |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | जब वर्तमान वस्तु निर्मित हुई थी, तब कन्स्ट्रक्टर को पास किया गया URI स्ट्रिंग लौटाता है। |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI के निरपेक्ष पथ और क्वेरी घटकों को प्रश्नचिह्न (?) द्वारा विभाजित करके लौटाता है। |
| **int32_t** [get_Port](./get_port/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI का पोर्ट नंबर लौटाता है। |
| [String](../string/) [get_Query](./get_query/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI में सम्मिलित क्वेरी जानकारी लौटाता है। |
| [String](../string/) [get_Scheme](./get_scheme/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI की स्कीम लौटाता है। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI के पथ खण्डों को शामिल करने वाली स्ट्रिंग्स की ऐरे लौटाता है। |
| **bool** [get_UserEscaped](./get_userescaped/)() const | निर्धारित करता है कि वर्तमान वस्तु के कन्स्ट्रक्टर को पास किया गया URI स्ट्रिंग पूरी तरह एस्केप्ड था या नहीं। |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI से जुड़ा उपयोगकर्ता नाम, पासवर्ड और अन्य उपयोगकर्ता जानकारी लौटाता है। |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | निर्दिष्ट एस्केपिंग का उपयोग करके URI के निर्दिष्ट घटकों को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | URI का हैश कोड प्राप्त करता है। |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI के निर्दिष्ट भाग को लौटाता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समान। |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | निर्दिष्ट वर्ण का हेक्साडेसिमल समतुल्य लौटाता है। |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | निर्दिष्ट हेक्साडेसिमल प्रतिनिधित्व को वर्ण में परिवर्तित करता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण प्रतिनिधित्व करती है। C# 'is' ऑपरेटर का समान। |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | निर्धारित करता है कि वर्तमान [Uri](./) वस्तु द्वारा प्रतिनिधित्व किया गया URI निर्दिष्ट [Uri](./) वस्तु द्वारा प्रतिनिधित्व किए गए URI की आधार है या नहीं। |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | निर्धारित करता है कि निर्दिष्ट वर्ण मान्य हेक्साडेसिमल अंक का प्रतिनिधित्व करता है या नहीं। |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में निर्दिष्ट स्थिति पर वर्ण हेक्साडेसिमल एन्कोडेड है या नहीं। |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | इंगित करता है कि इस [Uri](./) को बनाने के लिये उपयोग की गई स्ट्रिंग सही रूप से निर्मित थी और आगे एस्केप करने की आवश्यकता नहीं है। |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | निर्धारित करता है कि निर्दिष्ट स्ट्रिंग एक सही-formed URI है या नहीं। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | दो [Uri](./) इंस्टेंस के बीच अंतर निर्धारित करता है। |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | वर्तमान और निर्दिष्ट [Uri](./) वस्तुओं द्वारा प्रतिनिधित्व किए गए URI के बीच अंतर निर्धारित करता है। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरम्भ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरम्भ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ मान प्रकार की वस्तु की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट तर्क को कमजोर पॉइंटर (साझा नहीं) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](./tostring/)() const override | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए URI का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | निर्दिष्ट URI को प्रतिनिधित्व करने वाला [Uri](./) ऑब्जेक्ट बनाता है; एक तर्क URI प्रकार निर्दिष्ट करता है। |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | निर्दिष्ट [Uri](./) ऑब्जेक्ट (जो बेस URI प्रतिनिधित्व करता है) और सापेक्ष URI के स्ट्रिंग प्रतिनिधित्व से एक [Uri](./) ऑब्जेक्ट बनाता है। |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | निर्दिष्ट बेस और सापेक्ष URI से एक [Uri](./) ऑब्जेक्ट बनाता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | निर्दिष्ट एस्केप्ड स्ट्रिंग को अनएस्केप करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
|  [Uri](./uri/)(const [String](../string/)\&) | निर्दिष्ट URI को प्रतिनिधित्व करने वाला [Uri](./) ऑब्जेक्ट बनाता है। |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | निर्दिष्ट URI को प्रतिनिधित्व करने वाला [Uri](./) ऑब्जेक्ट बनाता है; एक तर्क यह निर्धारित करता है कि URI एस्केप्ड होना चाहिए या नहीं। |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | निर्दिष्ट [Uri](./) ऑब्जेक्ट (जो बेस URI प्रतिनिधित्व करता है) और सापेक्ष URI के स्ट्रिंग प्रतिनिधित्व से एक [Uri](./) ऑब्जेक्ट बनाता है; एक तर्क यह निर्धारित करता है कि URI एस्केप्ड होना चाहिए या नहीं। |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | निर्दिष्ट URI को प्रतिनिधित्व करने वाला [Uri](./) ऑब्जेक्ट बनाता है; एक तर्क URI प्रकार निर्दिष्ट करता है। |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | निर्दिष्ट बेस और सापेक्ष URI से एक [Uri](./) ऑब्जेक्ट बनाता है। |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | निर्दिष्ट बेस और सापेक्ष URI से एक [Uri](./) ऑब्जेक्ट बनाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | संचार प्रोटोकॉल स्कीम को [Uri](./) के पते भाग से अलग करने वाले अक्षरों को निर्दिष्ट करता है। |
| static [UriSchemeFile](./urischemefile/) | केवल यह बताता है कि [Uri](./) एक फ़ाइल का पॉइंटर है। |
| static [UriSchemeFtp](./urischemeftp/) | निर्दिष्ट करता है कि [Uri](./) फ़ाइल ट्रांसफर प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeGopher](./urischemegopher/) | निर्दिष्ट करता है कि [Uri](./) गफ़र प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeHttp](./urischemehttp/) | निर्दिष्ट करता है कि [Uri](./) हाइपरटेक्स्ट ट्रांसफ़र प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeHttps](./urischemehttps/) | निर्दिष्ट करता है कि [Uri](./) सुरक्षित हाइपरटेक्स्ट ट्रांसफ़र प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeMailto](./urischememailto/) | निर्दिष्ट करता है कि [Uri](./) एक ईमेल पता है और सरल मेल ट्रांसपोर्ट प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeNetPipe](./urischemenetpipe/) | निर्दिष्ट करता है कि [Uri](./) [Windows](../../system.windows/) कम्यूनिकेशन फाउंडेशन द्वारा प्रयुक्त NetPipe स्कीम के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeNetTcp](./urischemenettcp/) | निर्दिष्ट करता है कि [Uri](./) [Windows](../../system.windows/) कम्यूनिकेशन फाउंडेशन द्वारा प्रयुक्त NetTcp स्कीम के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeNews](./urischemenews/) | निर्दिष्ट करता है कि [Uri](./) इंटरनेट समाचार समूह है और नेटवर्क न्यूज़ ट्रांसपोर्ट प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |
| static [UriSchemeNntp](./urischemenntp/) | निर्दिष्ट करता है कि [Uri](./) इंटरनेट समाचार समूह है और नेटवर्क न्यूज़ ट्रांसपोर्ट प्रोटोकॉल के माध्यम से एक्सेस किया जाता है। |

## टिप्पणी

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## देखें भी

* क्लास [Object](../object/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)