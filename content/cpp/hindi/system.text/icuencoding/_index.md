---
title: ICUEncoding
second_title: Aspose.Slides for C++ API संदर्भ
description: "ICU-आधारित एन्कोडिंग कार्यान्वयन। केवल आंतरिक उपयोग के लिए। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 300
url: /hi/system.text/icuencoding/
---
## ICUEncoding क्लास

ICU-आधारित एनकोडिंग कार्यान्वयन। केवल आंतरिक उपयोग के लिए। इस क्लास की वस्तुएँ केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी नहीं बनायें, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों को तर्क के रूप में पास करने के लिए उपयोग करें।

```cpp
class ICUEncoding : public System::Text::Encoding
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | एनकोडिंग ऑब्जेक्ट को क्लोन करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | दो एनकोडिंग्स के बीच बाइट्स को परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | दो एनकोडिंग्स के बीच बाइट्स को परिवर्तित करता है। |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एनकोडिंग्स की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को ए‍म्यूलेट करता है जहाँ दो NaN समान माने जाते हैं, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को ए‍म्यूलेट करता है जहाँ दो NaN समान माने जाते हैं, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजन के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII एनकोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | स्टैंडर्ड बिग-एंडियन यूनिकोड एनकोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | स्टैंडर्ड बिग-एंडियन UTF-32 एनकोडिंग ऑब्जेक्ट प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | मेल एजेंट बॉडी के साथ संगत एनकोडिंग नाम प्राप्त करता है। |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | डिकोडर फॉलबैक प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | डिफ़ॉल्ट एनकोडिंग प्राप्त करता है। |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | एन्कोडर फॉलबैक प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | मानव-पठनीय एनकोडिंग नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | मेल एजेंट हेडर के साथ संगत एनकोडिंग नाम प्राप्त करता है। |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | जाँचता है कि क्या एनकोडिंग ब्राउज़र में सामग्री प्रदर्शित करने के लिए उपयोग की जा सकती है। |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | जाँचता है कि क्या एनकोडिंग ब्राउज़र में सामग्री सहेजने के लिए उपयोग की जा सकती है। |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | जाँचता है कि क्या एनकोडिंग मेल क्लाइंट में सामग्री प्रदर्शित करने के लिए उपयोग की जा सकती है। |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | जाँचता है कि क्या एनकोडिंग मेल क्लाइंट में सामग्री सहेजने के लिए उपयोग की जा सकती है। |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | जाँचता है कि एनकोडिंग केवल-पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | जाँचता है कि एनकोडिंग सिंगल बाइट है या नहीं। |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 एनकोडिंग प्राप्त करता है। केवल आंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | स्टैंडर्ड यूनिकोड एनकोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | स्टैंडर्ड UTF-7 एनकोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | स्टैंडर्ड UTF-8 एनकोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | केवल आंतरिक, क्लास लाइब्रेरीज़ द्वारा उपयोग हेतु: बिना मार्केड और गैर-इनपुट-वैधीकृत। |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA-संगत एनकोडिंग नाम प्राप्त करता है। |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI। |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI। |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI। |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI। |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI। |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | एक कैरेक्टर बफ़र को एन्कोड करने से उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक कैरेक्टरों की संख्या प्राप्त करता है। |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | एक बाइट बफ़र को डिकोड करने से उत्पन्न कैरेक्टर प्राप्त करता है। |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न कैरेक्टर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न कैरेक्टर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने से उत्पन्न कैरेक्टर प्राप्त करता है। |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | एक बाइट बफ़र को डिकोड करने से उत्पन्न कैरेक्टर प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | एक डिकोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट की ओर अग्रसारित करता है। |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | एक एन्कोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट की ओर अग्रसारित करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | नाम द्वारा एनकोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | कोडपेज द्वारा एनकोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | कोडपेज द्वारा एनकोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | नाम द्वारा एनकोडिंग प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | ज्ञात एनकोडिंग्स की सूची प्राप्त करता है। |
| int [GetHashCode](../encoding/gethashcode/)() const override | एनकोडिंग को हैश करता है। |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | निर्दिष्ट संख्या में कैरेक्टर्स को एन्कोड करने के लिए आवश्यक अधिकतम बाइट्स की संख्या प्राप्त करता है। |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | निर्दिष्ट बाइट्स को डिकोड करने के लिए आवश्यक अधिकतम कैरेक्टरों की संख्या प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | एक बाइट अनुक्रम लौटाता है जो एनकोडिंग को दर्शाता है (जैसे BOM)। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | कंस्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | कोडपेजों का उपयोग करके एनकोडिंग्स की तुलना करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | डिकोडर फॉलबैक सेट करता है। |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | एन्कोडर फॉलबैक सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाकर वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कन्वर्ट करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | डिफ़ॉल्ट कोडपेज मान। |

## संबंधित देखें

* क्लास [Encoding](../encoding/)
* नेमस्पेस [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)