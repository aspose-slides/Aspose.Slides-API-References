---
title: HttpUtility
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: सेवा क्लास जो URL भागों को एन्कोड और डिकोड करती है, हेक्स एस्केप फ्रैगमेंट्स से और उनमें।
type: docs
weight: 40
url: /hi/system.web/httputility/
---
## HttpUtility क्लास

Service class that encodes and decodes URL parts to and from hex escape fragments.

```cpp
class HttpUtility : public System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| static [String](../../system/string/) [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&) | HTML फ्रैगमेंट को डिकोड करता है। |
| static void [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | HTML फ्रैगमेंट को डिकोड करता है। |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&) | HTML फ्रैगमेंट को एन्कोड करता है। |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | HTML फ्रैगमेंट को एन्कोड करता है। |
| static void [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | HTML फ्रैगमेंट को एन्कोड करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/)) | स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है। |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है। |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | बाइट्स एरे से URI फ्रैगमेंट को डिकोड करता है। |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | बाइट्स एरे से URI फ्रैगमेंट को डिकोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | बाइट्स एरे से URI फ्रैगमेंट को डिकोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&) | बाइट्स स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | स्ट्रिंग से URI फ्रैगमेंट को डिकोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | बाइट्स एरे से URI फ्रैगमेंट को डिकोड करता है। |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/)) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/), const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | URI फ्रैगमेंट को एन्कोड करता है। |
| static [String](../../system/string/) [UrlEncodeUnicode](./urlencodeunicode/)(const [String](../../system/string/)\&) | Unicode का उपयोग करके URI फ्रैगमेंट को एन्कोड करता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const [String](../../system/string/)\&) | Unicode का उपयोग करके URI फ्रैगमेंट को एन्कोड करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Web](../)
* लाइब्रेरी [Aspose.Slides](../../)