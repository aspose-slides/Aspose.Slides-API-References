---
title: ASCIIEncoding
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "ASCII एन्कोडिंग का प्रतिनिधित्व करता है। इस क्लास के ऑब्जेक्ट को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करें।"
type: docs
weight: 1
url: /hi/system.text/asciiencoding/
---
## ASCIIEncoding क्लास

ASCII एन्कोडिंग का प्रतिनिधित्व करता है। इस क्लास के ऑब्जेक्ट को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या `new` ऑपरेटर का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करें।

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | कन्स्ट्रक्टर। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | एन्कोडिंग ऑब्जेक्ट को क्लोन करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | दो एन्कोडिंग के बीच बाइट्स को परिवर्तित करता है। |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एन्कोडिंग की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | मानक बिग-एंडियन यूनिकोड एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | मानक बिग-एंडियन UTF-32 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | मेल एजेंट बॉडी संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | डिकोडर फॉलबैक प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | एन्कोडर फॉलबैक प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | मानव-पठनीय एन्कोडिंग नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | मेल एजेंट हेडर संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | जांचता है कि एन्कोडिंग ब्राउज़र में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | जांचता है कि एन्कोडिंग ब्राउज़र में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | जांचता है कि एन्कोडिंग मेल क्लाइंट में सामग्री प्रदर्शित करने के लिए उपयोग किया जा सकता है या नहीं। |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | जांचता है कि एन्कोडिंग मेल क्लाइंट में सामग्री सहेजने के लिए उपयोग किया जा सकता है या नहीं। |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | जांचता है कि एन्कोडिंग केवल-पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | जांचता है कि एन्कोडिंग सिंगल बाइट है या नहीं। |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 एन्कोडिंग प्राप्त करता है। FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | मानक यूनिकोड एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | मानक UTF-7 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | मानक UTF-8 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | केवल आंतरिक, जिसे क्लास लाइब्रेरी द्वारा उपयोग किया जाता है: अनमार्क्ड और गैर-इनपुट-मान्यरण। |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA-संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI। |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI। |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI। |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करता है। |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | एक बाइट बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है। |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप उत्पन्न अक्षर प्राप्त करता है। |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप उत्पन्न अक्षर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप उत्पन्न अक्षर प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप उत्पन्न अक्षर प्राप्त करता है। |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप उत्पन्न अक्षर प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | एक डिकोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को फॉरवर्ड करता है। |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | एक एन्कोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को फॉरवर्ड करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | नाम द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | कोडपेज द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | कोडपेज द्वारा एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | नाम द्वारा एन्कोडिंग प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | ज्ञात एन्कोडिंग की सूची प्राप्त करता है। |
| int [GetHashCode](../encoding/gethashcode/)() const override | एन्कोडिंग का हैश बनाता है। |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | ज्ञात अक्षर गिनती वाले स्ट्रिंग को रखने के लिये अधिकतम बाइट गिनती प्राप्त करता है। |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | निर्दिष्ट बाइट गिनती को डिकोड करने के लिये आवश्यक अधिकतम अक्षर संख्या प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | ऐसे बाइट अनुक्रम को लौटाता है जो एन्कोडिंग दर्शाता है (जैसे BOM)। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | बाइट बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | कन्स्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कन्स्ट्र्शन को सक्षम करता है। |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | कोडपेज का उपयोग करके एन्कोडिंग की तुलना करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-कम्पेयर मान-टाइप ऑब्जेक्ट को nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग के मामलों के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | डिकोडर फॉलबैक सेट करता है। |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | एन्कोडर फॉलबैक सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंट मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अन-लॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI। |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | डिफ़ॉल्ट कोडपेज मान। |

## संबंधित देखें

* क्लास [ICUEncoding](../icuencoding/)
* नामस्थान [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)