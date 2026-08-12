---
title: UTF7Encoding
second_title: Aspose.Slides for C++ API संदर्भ
description: "UTF-7 एन्कोडिंग। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 365
url: /hi/system.text/utf7encoding/
---
## UTF7Encoding वर्ग

UTF-7 एनकोडिंग। इस वर्ग की वस्तुएँ केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## विधियाँ

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | एन्कोडिंग ऑब्जेक्ट की क्लोन बनाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | दो एन्कोडिंग्स के बीच बाइट्स को परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | दो एन्कोडिंग्स के बीच बाइट्स को परिवर्तित करता है। |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | ऑब्जेक्ट के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सार के अनुसार करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के समान नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के समान नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | मानक बिग-एंडियन Unicode एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | मानक बिग-एंडियन UTF-32 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | मेल एजेंट बॉडी के साथ संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | डिकोडर फॉलबैक प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | एन्कोडर फॉलबैक प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | पढ़ने योग्य एन्कोडिंग नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | मेल एजेंट हेडर के साथ संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | जाँचता है कि क्या एन्कोडिंग को ब्राउज़र में सामग्री दिखाने के लिए उपयोग किया जा सकता है। |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | जाँचता है कि क्या एन्कोडिंग को ब्राउज़र में सामग्री सहेजने के लिए उपयोग किया जा सकता है। |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | जाँचता है कि क्या एन्कोडिंग को मेल क्लाइंट में सामग्री दिखाने के लिए उपयोग किया जा सकता है। |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | जाँचता है कि क्या एन्कोडिंग को मेल क्लाइंट में सामग्री सहेजने के लिए उपयोग किया जा सकता है। |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | जाँचता है कि एन्कोडिंग केवल-रीड है या नहीं। |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | जाँचता है कि एन्कोडिंग सिंगल बाइट है या नहीं। |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 एन्कोडिंग प्राप्त करता है। अंतरिक उपयोग के लिए। |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | मानक Unicode एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | मानक UTF-7 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | मानक UTF-8 एन्कोडिंग ऑब्जेक्ट प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | केवल आंतरिक, वर्ग लाइब्रेरी द्वारा उपयोग हेतु: अनमार्क्ड और गैर-इनपुट-वैधता। |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA-संगत एन्कोडिंग नाम प्राप्त करता है। |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) कोडपेज ID प्राप्त करता है। |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | एक कैरैक्टर बफ़र को एन्कोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | एक कैरैक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स। |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | एक बाइट बफ़र को डिकोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | एक बाइट बफ़र को डिकोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | एक बाइट बफ़र को डिकोड करने के लिये आवश्यक कैरैक्टरों की संख्या प्राप्त करता है। |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप प्राप्त अक्षर। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | एक डिकोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को फ़ॉरवर्ड करता है। |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | एक एन्कोडर प्राप्त करता है जो अनुरोधों को इस ऑब्जेक्ट को फ़ॉरवर्ड करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | नाम से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | कोडपेज से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | कोडपेज से एन्कोडिंग प्राप्त करता है। |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | नाम से एन्कोडिंग प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | ज्ञात एन्कोडिंग्स की सूची प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | एन्कोडिंग हैश कोड प्राप्त करता है। |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | निर्दिष्ट संख्या के कैरैक्टरों को एन्कोड करने के लिये आवश्यक अधिकतम बाइट्स की संख्या प्राप्त करता है। |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | निर्दिष्ट संख्या के बाइट्स को डिकोड करने के लिये आवश्यक अधिकतम कैरैक्टरों की संख्या प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | एन्कोडिंग को दर्शाने वाले बाइट्स की श्रृंखला (जैसे BOM) लौटाता है। |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | एन्कोडिंग पैरामीटरों की तुलना करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | डिकोडर फॉलबैक सेट करता है। |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | एन्कोडर फॉलबैक सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'tवें टेम्पलेट आर्गुमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
|  [UTF7Encoding](./utf7encoding/)() | कन्स्ट्रक्टर। |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | कन्स्ट्रक्टर। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | डिफ़ॉल्ट कोडपेज मान। |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | [Windows](../../system.windows/) द्वारा UTF-7 कोडपेज id के लिये प्रयोग किया गया मैजिक नंबर। |

## संबंधित देखें

* क्लास [Encoding](../encoding/)
* नेमस्पेस [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)