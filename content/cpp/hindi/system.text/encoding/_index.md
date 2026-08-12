---
title: Encoding
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एन्कोडिंग सेवाएँ।
type: docs
weight: 222
url: /hi/system.text/encoding/
---
## एन्कोडिंग क्लास

[Encoding](./) सेवाएँ।

```cpp
class Encoding : public System::Object
```

## विधियां

| मेथड | विवरण |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | एन्कोडिंग ऑब्जेक्ट को क्लोन करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एन्कोडिंग की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता, फिर भी दो NaN को समान मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता, फिर भी दो NaN को समान मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | ASCII एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | मानक बिग-एंडियन Unicode एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | मानक बिग-एंडियन UTF-32 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | मेल एजेंट बॉडी संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_CodePage](./get_codepage/)() | [Windows](../../system.windows/) कोडपेज आईडी प्राप्त करता है। |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | डिकोडर फ़ॉलबैक प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | एन्कोडर फ़ॉलबैक प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | मानव-पठनीय एन्कोडिंग नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | मेल एजेंट हेडर संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | जाँचता है कि एन्कोडिंग को ब्राउज़र में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | जाँचता है कि एन्कोडिंग को ब्राउज़र में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | जाँचता है कि एन्कोडिंग को मेल क्लाइंट में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | जाँचता है कि एन्कोडिंग को मेल क्लाइंट में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | जाँचता है कि एन्कोडिंग केवल-पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | जाँचता है कि एन्कोडिंग सिंगल बाइट है या नहीं। |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Latin1 एन्कोडिंग प्राप्त करता है। आंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | मानक Unicode एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | मानक UTF-7 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | मानक UTF-8 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | केवल आंतरिक, क्लास लाइब्रेरीज द्वारा उपयोग के लिए: अनमार्क्ड और गैर-इनपुट-वैधता। |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | IANA-संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | [Windows](../../system.windows/) कोडपेज आईडी प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | एक स्ट्रिंग को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | एक कैरेक्टर बफ़र को एन्कोड करने पर प्राप्त बाइट्स प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | एक बाइट बफ़र को डिकोड करने पर प्राप्त कैरेक्टर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने पर प्राप्त कैरेक्टर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने पर प्राप्त कैरेक्टर प्राप्त करता है। |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | एक बाइट बफ़र को डिकोड करने पर प्राप्त कैरेक्टर प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट के साथ जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | ऐसा डिकोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट की ओर अग्रसर करता है। |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | ऐसा एन्कोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट की ओर अग्रसर करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | नाम से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | कोडपेज से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | कोडपेज से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | नाम से एन्कोडिंग प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | ज्ञात एन्कोडिंग की सूची प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | एन्कोडिंग को हैश करता है। |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | निर्दिष्ट संख्या के कैरेक्टरों को एन्कोड करने के लिए आवश्यक अधिकतम बाइट्स की संख्या प्राप्त करता है। |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | निर्दिष्ट संख्या के बाइट्स को डिकोड करने के लिए आवश्यक अधिकतम कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | एन्कोडिंग को दर्शाने वाले बाइट्स की श्रृंखला लौटाता है (उदा. BOM)। |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानान्तर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानान्तर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानान्तर। कस्टम टाइप्स को क्लोन करने को सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | डिकोडर फ़ॉलबैक सेट करता है। |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | एन्कोडर फ़ॉलबैक सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्प्लेट के n'th तर्क को वीक पॉइंटर (न कि शेयरड) सेट करता है। कंटेनर्स में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | डिफ़ॉल्ट कोडपेज मान। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)