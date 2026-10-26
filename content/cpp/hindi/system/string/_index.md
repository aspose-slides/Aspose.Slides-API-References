---
title: String
second_title: Aspose.Slides for C++ API संदर्भ
description: "String क्लास लाइब्रेरी में व्यापक रूप से उपयोग की जाती है। कोड अनुवाद करते समय यह C# System.String का विकल्प है। अनुकूलन कारणों से इसे Object उपवर्ग नहीं माना जाता। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और मान या संदर्भ द्वारा फ़ंक्शन को पास किया जाना चाहिए। इस प्रकार के ऑब्जेक्ट को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 1275
url: /hi/system/string/
---
## String वर्ग


[String](./) वर्ग पुस्तकालय में व्यापक रूप से उपयोग किया जाता है। कोड का अनुवाद करते समय C# [System.String](./) का विकल्प है। ऑप्टिमाइज़ेशन कारणों से, इसे [Object](../object/) उपवर्ग माना नहीं जाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) वर्ग का उपयोग न करें।

```cpp
class String
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) C++ पक्ष पर एक value type है जो स्पष्ट रूप से (बिना विरासत के) कुछ interfaces को लागू करता है। |
| const UChar * [begin](./begin/)() const | वास्तविक स्ट्रिंग बफ़र की शुरुआत की ओर संकेतक लौटाता है। कभी कुछ भी पुनः आवंटित नहीं करता। यह गारंटी नहीं देता कि बफ़र null-terminated है। |
| [String](./) [Clone](./clone/)() const | वर्तमान स्ट्रिंग की एक प्रति बनाता है। |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | दो उपस्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | दो उपस्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है। |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है, ordinal मोड का उपयोग करते हुए। |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | दो स्ट्रिंग्स की less-equal-greater तुलना करता है, ordinal मोड का उपयोग करते हुए। |
| int [CompareTo](./compareto/)(const [String](./)\&) const | ‘less-equals-more’ शैली में दो स्ट्रिंग्स की तुलना करता है। वर्तमान संस्कृति का उपयोग करता है। |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | स्ट्रिंग्स को जोड़ता है। |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | स्ट्रिंग्स को जोड़ता है। |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | स्ट्रिंग्स को जोड़ता है। |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | स्ट्रिंग्स को जोड़ता है। |
| **bool** [Contains](./contains/)(const [String](./)\&) const | जांचता है कि str वर्तमान स्ट्रिंग का उपस्ट्रिंग है या नहीं। |
| **bool** [Contains](./contains/)(char16_t) const | जांचता है कि स्ट्रिंग में दिया गया अक्षर मौजूद है या नहीं। |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | स्ट्रिंग की प्रति बनाता है। |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | स्ट्रिंग के अक्षरों को मौजूदा एरे तत्वों में कॉपी करता है। कोई आकार बदलाव नहीं किया जाता। |
| const UChar * [end](./end/)() const | वास्तविक स्ट्रिंग बफ़र के अंत की ओर संकेतक लौटाता है। कभी कुछ भी पुनः आवंटित नहीं करता। यह गारंटी नहीं देता कि बफ़र null-terminated है। |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | जांचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है या नहीं। |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | जांचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है या नहीं। |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | जांचता है कि स्ट्रिंग निर्दिष्ट उपस्ट्रिंग के साथ समाप्त होती है या नहीं। |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) समानता तुलना। StringComparison enumeration द्वारा प्रदान किए गए कई मोड समर्थित हैं। |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) समानता तुलना। [System::StringComparison::Ordinal](../stringcomparison/) तुलना मोड का उपयोग करता है। |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Ordinal तुलना मोड का उपयोग करके दो स्ट्रिंग्स की समानता तुलना करता है। |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | दो स्ट्रिंग्स की समानता तुलना करता है। |
| int [FastToAscii](./fasttoascii/)(char, int) const | [String](./) को ASCII स्ट्रिंग में बदलने का प्रयास करता है। |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | C# शैली में स्ट्रिंग को फॉर्मेट करता है। |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | C# शैली में स्ट्रिंग को फॉर्मेट करता है। |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | C# शैली में स्ट्रिंग को फॉर्मेट करता है। |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | C# शैली में स्ट्रिंग को फॉर्मेट करता है। |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | C# शैली में स्ट्रिंग को फॉर्मेट करता है। |
| static [String](./) [FromAscii](./fromascii/)(const char *) | ASCII स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | ASCII स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | ASCII स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | utf16 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | utf32 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | utf8 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | utf8 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | utf8 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | utf8 स्ट्रिंग से [String](./) बनाता है। |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | widestring से [String](./) बनाता है। |
| int [get_Length](./get_length/)() const | स्ट्रिंग की लंबाई प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const | स्ट्रिंग का हैश बनाता है। ICU में लागू, C# के हैश से मेल नहीं खाता। |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | सबस्ट्रिंग फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(char_t, int) const | अक्षर फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(char_t, int, int) const | सबस्ट्रिंग में अक्षर फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | सबस्ट्रिंग फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | सबस्ट्रिंग फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | सबस्ट्रिंग फ़ॉरवर्ड लुकअप। |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | सबस्ट्रिंग फ़ॉरवर्ड लुकअप। |
| int [IndexOfAny](./indexofany/)(char_t, int) const | अक्षर फ़ॉरवर्ड लुकअप। |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | स्ट्रिंग में str के सभी अक्षरों को क्रमशः खोजता है। यदि पहला अक्षर मिलता है तो उसकी स्थिति लौटाता है, अन्यथा दूसरा ढूँढता है आदि। |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | पूरी स्ट्रिंग में पास किए गए किसी भी अक्षर की तलाश करता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा आदि। पहले मिलते लक्ष्य अक्षर का सूचकांक लौटाता है। |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | सबस्ट्रिंग में पास किए गए किसी भी अक्षर की तलाश करता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा आदि। पहले मिलते लक्ष्य अक्षर का सूचकांक लौटाता है। |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | सबस्ट्रिंग में पास किए गए किसी भी अक्षर की तलाश करता है। पहला स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर दूसरा आदि। पहले मिलते लक्ष्य अक्षर का सूचकांक लौटाता है। |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | निर्दिष्ट स्थिति पर सबस्ट्रिंग डालता है। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | जांचता है कि स्ट्रिंग ऑब्जेक्ट [TypeInfo](../typeinfo/) द्वारा निर्दिष्ट प्रकार का है या नहीं। |
| **bool** [IsAsciiString](./isasciistring/)() const | जाँचता है कि [String](./) केवल ASCII प्रतीकों को ही सम्मिलित करता है। |
| **bool** [IsEmpty](./isempty/)() const | जांचता है कि स्ट्रिंग न तो null है और न ही खाली है। |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | जांचता है कि यूनिकोड स्ट्रिंग निर्दिष्ट नॉर्मलाइज़ेशन फॉर्म के द्वारा सामान्यीकृत है या नहीं। |
| **bool** [IsNull](./isnull/)() const | जांचता है कि स्ट्रिंग को null माना जाता है। [String](./) null है और केवल तभी जब वह [String()](./string/) कंस्ट्रक्टर द्वारा निर्मित, मूव, कॉपी या null स्ट्रिंग से असाइन किया गया हो या [reset()](./reset/) मेथड को कॉल किया गया हो। |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | जांचता है कि स्ट्रिंग खाली है या null माना जाता है। |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | जांचता है कि पास की गई स्ट्रिंग null या खाली है। |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | निर्दिष्ट स्ट्रिंग null, खाली या सिर्फ़ whitespace अक्षरों से बनी है या नहीं, दर्शाता है। |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | स्ट्रिंग को सेपरेटर के रूप में उपयोग करके एरे जोड़ता है। |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | स्ट्रिंग को सेपरेटर के रूप में उपयोग करके एरे जोड़ता है। |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | स्ट्रिंग को सेपरेटर के रूप में उपयोग करके एरे जोड़ता है। |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | स्ट्रिंग को सेपरेटर के रूप में उपयोग करके एरे जोड़ता है। |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | सबस्ट्रिंग बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | सबस्ट्रिंग बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | सबस्ट्रिंग बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | सबस्ट्रिंग बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(char_t) const | अक्षर बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | अक्षर बैकवर्ड लुकअप। |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | अक्षर बैकवर्ड लुकअप। |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | पूरी स्ट्रिंग में पास किए गए किसी भी अक्षर को पीछे की ओर खोजता है। आखिरी स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर पिछले आदि। पहला मिलते लक्ष्य का इंडेक्स लौटाता है। |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | सबस्ट्रिंग में पास किए गए किसी भी अक्षर को पीछे की ओर खोजता है। आखिरी स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर पिछले आदि। पहला मिलते लक्ष्य का इंडेक्स लौटाता है। |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | सबस्ट्रिंग में पास किए गए किसी भी अक्षर को पीछे की ओर खोजता है। आखिरी स्ट्रिंग अक्षर को anyOf के सभी अक्षरों से तुलना करता है, फिर पिछले आदि। पहला मिलते लक्ष्य का इंडेक्स लौटाता है। |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | निर्दिष्ट नॉर्मलाइज़ेशन फॉर्म के साथ यूनिकोड स्ट्रिंग को सामान्यीकृत करता है। |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | स्ट्रिंग को रीड-ओनली स्पैन में परिवर्तित करता है। |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | असमानता तुलना ऑपरेटर। |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | जांचता है कि स्ट्रिंग null नहीं है। [IsNull()](./isnull/) कॉल जैसी ही तर्क लागू करता है। |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) कंकैटनेशन ऑपरेटर। |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) लिटरल या किरैक्टर स्ट्रिंग पॉइंटर के साथ कंकैटनेशन करता है। |
| [String](./) [operator+](./operator_plus/)(char_t) const | स्ट्रिंग की अंत में अक्षर जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(int) const | स्ट्रिंग की अंत में पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | स्ट्रिंग की अंत में unsigned पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(**double**) const | स्ट्रिंग की अंत में फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | स्ट्रिंग की अंत में पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(const T\&) const | स्ट्रिंग की अंत में रेफ़रेंस प्रकार ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(const T\&) const | स्ट्रिंग की अंत में रेफ़रेंस प्रकार ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./) [operator+](./operator_plus/)(T) const | स्ट्रिंग की अंत में बूलियन मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | कंकैटनेशन असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | कंकैटनेशन असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | कंकैटनेशन असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | कंकैटनेशन असाइनमेंट ऑपरेटर।
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | संलग्न असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | संलग्न असाइनमेंट ऑपरेटर। |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | स्ट्रिंग्स को क्रम में तुलना करता है। |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | असाइनमेंट ऑपरेटर। |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | समानता तुलना ऑपरेटर। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि स्ट्रिंग शून्य है। [IsNull()](./isnull/) कॉल के समान तर्क लागू करता है। |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | स्ट्रिंग्स को क्रम में तुलना करता है। |
| char_t [operator[]](./operator[]/)(int) const | निर्दिष्ट स्थिति पर अक्षर प्राप्त करता है। |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | मूल स्ट्रिंग के बाएँ तरफ पैडिंग जोड़ता है। |
| [String](./) [PadRight](./padright/)(int, char_t) const | मूल स्ट्रिंग के दाएँ तरफ पैडिंग जोड़ता है। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | वास्तविक स्ट्रिंग बफर के अंतिम अक्षर (यदि कोई हो) के लिए रिवर्स इटरेटर लौटाता है। |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | वर्तमान स्ट्रिंग से सबस्ट्रिंग को छोड़कर सब कुछ निकालता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | वास्तविक स्ट्रिंग बफर के पहले अक्षर से पहले (यदि कोई हो) के लिए रिवर्स इटरेटर लौटाता है। |
| [String](./) [Replace](./replace/)(char_t, char_t) const | स्ट्रिंग में अक्षर की सभी घटनाओं को बदलता है। |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | इस स्ट्रिंग में लुकअप की सभी घटनाओं को बदलता है। |
| [String](./)\& [reset](./reset/)() | स्ट्रिंग को शून्य सेट करता है। यह C# में 'string_variable_name = null' के समान है। |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | निर्दिष्ट स्थिति पर अक्षर सेट करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को अक्षर द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को अक्षर द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को दो अक्षरों में से एक द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को निर्दिष्ट किए गए अक्षरों में से एक द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को निर्दिष्ट किए गए अक्षरों में से एक द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को सबस्ट्रिंग द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को सबस्ट्रिंग द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को सबस्ट्रिंग द्वारा विभाजित करता है। |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | स्ट्रिंग को सबस्ट्रिंग द्वारा विभाजित करता है। वर्तमान में केवल शून्य या एक तत्व वाले सेपरेटर्स एरे का समर्थन करता है। |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | जाँचता है कि स्ट्रिंग निर्दिष्ट सबस्ट्रिंग से शुरू होती है। |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | जाँचता है कि स्ट्रिंग निर्दिष्ट सबस्ट्रिंग से शुरू होती है। |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | जाँचता है कि स्ट्रिंग निर्दिष्ट सबस्ट्रिंग से शुरू होती है। |
|  [String](./string/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। स्ट्रिंग ऑब्जेक्ट बनाता है जिसे शून्य माना जाता है। |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | स्ट्रिंग लिटरल के आधार पर स्ट्रिंग बनाता है। लिटरल को नल-टर्मिनेटेड स्ट्रिंग मानता है, लिटरल आकार के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | कैरेक्टर स्ट्रिंग पॉइंटर के आधार पर स्ट्रिंग बनाता है। पॉइंटेड स्ट्रिंग को नल-टर्मिनेटेड मानता है, नल कैरेक्टर के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | स्ट्रिंग लिटरल के आधार पर स्ट्रिंग बनाता है। UTF8 में लिटरल को नल-टर्मिनेटेड स्ट्रिंग मानता है, लिटरल आकार के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | UTF8 में पॉइंटेड स्ट्रिंग को नल-टर्मिनेटेड मानता है, नल कैरेक्टर के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। |
|  [String](./string/)(const char16_t *, int) | कैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है। |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | निर्दिष्ट रीड-ओनली स्पैन में दर्शाए गए यूनिकोड कैरेक्टर के साथ [System.String](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [String](./string/)(const char *, int) | कैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है। |
|  [String](./string/)(const char16_t *, int, int) | शुरुआती स्थिति से लंबाई का उपयोग करके कैरेक्टर स्ट्रिंग पॉइंटर से स्ट्रिंग बनाता है। |
| explicit  [String](./string/)(const char16_t, int) | फ़िल कन्स्ट्रक्टर। |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | नलपॉइंट कन्स्ट्रक्टर। अन्य टेम्पलेट कन्स्ट्रक्टर्स के साथ प्राथमिकताओं को हल करने के लिए टेम्पलेट के रूप में घोषित किया गया है। |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | वाइडस्ट्रिंग लिटरल के आधार पर स्ट्रिंग बनाता है। लिटरल को नल-टर्मिनेटेड स्ट्रिंग मानता है, लिटरल आकार के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। कुछ प्लेटफ़ॉर्म पर **wchar_t** से कन्वर्ज़न समय-साध्य है, इसलिए कोई अप्रत्यक्ष रूपांतरण की अनुमति नहीं है। |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | वाइडकैरेक्टर स्ट्रिंग पॉइंटर के आधार पर स्ट्रिंग बनाता है। पॉइंटेड स्ट्रिंग को नल-टर्मिनेटेड मानता है, नल कैरेक्टर के आधार पर लक्ष्य स्ट्रिंग की लंबाई की गणना करता है। कुछ प्लेटफ़ॉर्म पर **wchar_t** से कन्वर्ज़न समय-साध्य है, इसलिए कोई अप्रत्यक्ष रूपांतरण की अनुमति नहीं है। |
| explicit  [String](./string/)(const **wchar_t** *, int) | वाइडकैरेक्टर स्ट्रिंग पॉइंटर और स्पष्ट लंबाई से स्ट्रिंग बनाता है। कुछ प्लेटफ़ॉर्म पर **wchar_t** से कन्वर्ज़न समय-साध्य है, इसलिए कोई अप्रत्यक्ष रूपांतरण की अनुमति नहीं है। |
| explicit  [String](./string/)(const **wchar_t**, int) | फ़िल कन्स्ट्रक्टर। कुछ प्लेटफ़ॉर्म पर **wchar_t** से कन्वर्ज़न समय-साध्य है, इसलिए कोई अप्रत्यक्ष रूपांतरण की अनुमति नहीं है। |
|  [String](./string/)(const [String](./)\&) | कॉपी कन्स्ट्रक्टर। |
|  [String](./string/)([String](./)\&&) | मूव कन्स्ट्रक्टर। |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | पूरे कैरेक्टर एरे को स्ट्रिंग में परिवर्तित करता है। |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | कैरेक्टर एरे के सबरेंज को स्ट्रिंग में परिवर्तित करता है। यदि पैरामीटर एरे की सीमा से बाहर हैं, तो खाली स्ट्रिंग बनायी जाती है। |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | UnicodeString को [String](./) में रैप करता है। |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | मूव कन्स्ट्रक्टर। |
| explicit  [String](./string/)(const std::wstring\&) | [String](./) को वाइडस्ट्रिंग से बनाता है। |
| explicit  [String](./string/)(const std::u16string\&) | [String](./) को utf16 स्ट्रिंग से बनाता है। |
| explicit  [String](./string/)(const std::string\&) | UTF-8 फ़ॉर्मेट में प्रस्तुत std::string से [String](./) बनाता है। |
| explicit  [String](./string/)(const std::u32string\&) | std::u32string स्ट्रिंग से [String](./) बनाता है। |
| [String](./) [Substring](./substring/)(**int32_t**) const | सबस्ट्रिंग निकालता है। |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | सबस्ट्रिंग निकालता है। |
| std::string [ToAsciiString](./toasciistring/)() const | स्ट्रिंग को std::string में परिवर्तित करता है। ASCII एन्कोडिंग का उपयोग करता है। |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | स्ट्रिंग या सबस्ट्रिंग को बाइट्स की एरे में परिवर्तित करता है। |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | स्ट्रिंग या सबस्ट्रिंग को कैरेक्टर्स की एरे में परिवर्तित करता है। |
| [String](./) [ToLower](./tolower/)() const | सभी स्ट्रिंग के कैरेक्टर्स को लोअर केस में बदलता है। |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | विशिष्ट संस्कृति का उपयोग करके सभी स्ट्रिंग के कैरेक्टर्स को लोअर केस में बदलता है। |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | इनवैरिएंट संस्कृति का उपयोग करके सभी स्ट्रिंग के कैरेक्टर्स को लोअर केस में बदलता है। |
| [String](./) [ToString](./tostring/)() const | [String](./) क्लास को संभालने के लिए रैपर, जहाँ [ToString()](./tostring/) को वैल्यू टाइप ऑब्जेक्ट्स पर कॉल किया जा रहा है। |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | [String](./) क्लास को संभालने के लिए रैपर, जहाँ [ToString()](./tostring/) को वैल्यू टाइप ऑब्जेक्ट्स पर कॉल किया जा रहा है। |
| std::u16string [ToU16Str](./tou16str/)() const | स्ट्रिंग को std::u16string में परिवर्तित करता है। |
| std::u32string [ToU32Str](./tou32str/)() const | स्ट्रिंग को std::u32string में परिवर्तित करता है। |
| [String](./) [ToUpper](./toupper/)() const | सभी स्ट्रिंग के कैरेक्टर्स को अपर केस में बदलता है। |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | विशिष्ट संस्कृति का उपयोग करके सभी स्ट्रिंग के कैरेक्टर्स को अपर केस में बदलता है। |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | इनवैरिएंट संस्कृति का उपयोग करके सभी स्ट्रिंग के कैरेक्टर्स को अपर केस में बदलता है। |
| std::string [ToUtf8String](./toutf8string/)() const | स्ट्रिंग को std::string में परिवर्तित करता है। UTF-8 एन्कोडिंग का उपयोग करता है। |
| std::wstring [ToWCS](./towcs/)() const | स्ट्रिंग को std::wstring में परिवर्तित करता है। |
| [String](./) [Trim](./trim/)() const | स्ट्रिंग की शुरुआत और अंत दोनों से सभी व्हाइटस्पेस कैरेक्टर्स को हटाता है। |
| [String](./) [Trim](./trim/)(char_t) const | स्ट्रिंग की शुरुआत और अंत दोनों से पास किए गए कैरेक्टर की सभी घटनाओं को हटाता है। |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | स्ट्रिंग की शुरुआत और अंत दोनों से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | स्ट्रिंग की शुरुआत और अंत दोनों से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| [String](./) [TrimEnd](./trimend/)() const | स्ट्रिंग के अंत से सभी व्हाइटस्पेस कैरेक्टर्स को हटाता है। |
| [String](./) [TrimEnd](./trimend/)(char_t) const | स्ट्रिंग के अंत से पास किए गए कैरेक्टर की सभी घटनाओं को हटाता है। |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | स्ट्रिंग के अंत से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | स्ट्रिंग के अंत से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| [String](./) [TrimStart](./trimstart/)() const | स्ट्रिंग की शुरुआत से सभी व्हाइटस्पेस कैरेक्टर्स को हटाता है। |
| [String](./) [TrimStart](./trimstart/)(char_t) const | स्ट्रिंग की शुरुआत से पास किए गए कैरेक्टर की सभी घटनाओं को हटाता है। |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | स्ट्रिंग की शुरुआत से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | स्ट्रिंग की शुरुआत से पास किए गए कैरेक्टर्स की सभी घटनाओं को हटाता है। |
| const UChar * [u_str](./u_str/)() const | ICU-स्टाइल नल-टर्मिनेटेड बफ़र लौटाता है। स्ट्रिंग को पुन: आवंटित कर सकता है। |
|  [~String](./~string/)() | विनाशक। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Empty](./empty/) | खाली स्ट्रिंग। |
| static [Null](./null/) | शून्य स्ट्रिंग। |

## टाइपडेफ़

| टाइपडेफ़ | विवरण |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटररेटर प्रकार। |

## टिप्पणी

```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // एरे चर से स्ट्रिंग बनाएं और उसे प्रिंट करें।
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // एरे बाइट्स से स्ट्रिंग बनाएं और उसे प्रिंट करें।
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // नीचे की स्ट्रिंग को ट्रिम करें और प्रिंट करें।
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // स्ट्रिंग में शब्दों की संख्या प्रिंट करें।
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्न आउटपुट देता है:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)