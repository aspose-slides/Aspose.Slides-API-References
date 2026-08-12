---
title: Latin1Encoding
second_title: Aspose.Slides for C++ API संदर्भ
description: "Latin1 एन्कोडिंग समर्थन। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां उत्पन्न होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करने के लिए उपयोग करें।"
type: docs
weight: 313
url: /hi/system.text/latin1encoding/
---
## Latin1Encoding क्लास

Latin1 एन्कोडिंग समर्थन। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करने के लिए उपयोग करें।

```cpp
class Latin1Encoding : public System::Text::ICUEncoding
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | एन्कोडिंग ऑब्जेक्ट की क्लोन बनाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एन्कोडिंग की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल अंतरिक प्रयोजनों के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | स्टैंडर्ड बिग-एंडियन यूनिकोड एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | स्टैंडर्ड बिग-एंडियन UTF-32 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | मेल एजेंट बॉडी संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) कोडपेज आईडी प्राप्त करता है। |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | डिकोडर फॉलबैक प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | एन्कोडर फॉलबैक प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | मानव-पठनीय एन्कोडिंग नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | मेल एजेंट हेडर संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | जांचता है कि एन्कोडिंग को ब्राउज़र में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | जांचता है कि एन्कोडिंग को ब्राउज़र में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | जांचता है कि एन्कोडिंग को मेल क्लाइंट में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | जांचता है कि एन्कोडिंग को मेल क्लाइंट में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | जांचता है कि एन्कोडिंग केवल- पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | जांचता है कि एन्कोडिंग सिंगल बाइट है या नहीं। |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 एन्कोडिंग प्राप्त करता है। आंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | स्टैंडर्ड यूनिकोड एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | स्टैंडर्ड UTF-7 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | स्टैंडर्ड UTF-8 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | केवल आंतरिक, क्लास लाइब्रेरी द्वारा उपयोग के लिए: अनमार्क्ड और गैर-इनपुट-वैधता। |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA-संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) कोडपेज आईडी प्राप्त करता है। |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI। |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI। |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | एक बाइट बफ़र को डिकोड करने से उत्पन्न अक्षर प्राप्त करता है। |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न अक्षर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न अक्षर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने से उत्पन्न अक्षर प्राप्त करता है। |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न अक्षर प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | ऐसा डिकोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को अग्रेषित करता है। |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | ऐसा एन्कोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को अग्रेषित करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | नाम द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | कोडपेज द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | कोडपेज द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | नाम द्वारा एन्कोडिंग प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | ज्ञात एन्कोडिंग की सूची प्राप्त करता है। |
| int [GetHashCode](../encoding/gethashcode/)() const override | एन्कोडिंग का हैश बनाता है। |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | निर्दिष्ट संख्या में अक्षरों को एन्कोड करने के लिए आवश्यक अधिकतम बाइट्स की संख्या प्राप्त करता है। |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | निर्दिष्ट संख्या में बाइट्स को डिकोड करने के लिए आवश्यक अधिकतम अक्षरों की संख्या प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | एन्कोडिंग दर्शाने वाले बाइट्स की श्रृंखला (जैसे BOM) लौटाता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल के समान। |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | कंस्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर के समान। |
|  [Latin1Encoding](./latin1encoding/)() | कंस्ट्रक्टर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड के समान। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | कोडपेज का उपयोग करके एन्कोडिंग की तुलना करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नल पॉइंटर केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | डिकोडर फॉलबैक सेट करता है। |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | एन्कोडर फॉलबैक सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'th' टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड के समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | डिफ़ॉल्ट कोडपेज मान। |
| static constexpr [LATIN1_CODE_PAGE](./latin1_code_page/) | कोडपेज। |

## सम्बंधित देखें

* क्लास [ICUEncoding](../icuencoding/)
* नेमस्पेस [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)