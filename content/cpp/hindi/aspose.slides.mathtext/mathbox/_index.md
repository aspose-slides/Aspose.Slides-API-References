---
title: MathBox
second_title: Aspose.Slides for C++ API संदर्भ
description: गणितीय तत्व की तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट संरेखण बिंदु के साथ या बिना ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक बिंदु के रूप में उपयोग हो सकता है, या ऐसा समूहित किया जा सकता है जिससे उसके भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के रूप में, \"==\" ऑपरेटर को लाइन ब्रेक रोकने के लिए बॉक्स्ड किया जाना चाहिए।
type: docs
weight: 742
url: /hi/aspose.slides.mathtext/mathbox/
---
## MathBox वर्ग

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the \"==\" operator should be boxed to prevent line breaks.

```cpp
class MathBox : public Aspose::Slides::MathText::MathElementBase,
                public Aspose::Slides::MathText::IMathBox,
                public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | ऊपर इस तत्व पर एक उच्चारण चिह्न (इस तत्व के शीर्ष पर एक अक्षर) सेट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस उदाहरण को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | इस उदाहरण को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार की एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार की एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | गणितीय तत्व को कोष्ठकों में घेरता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | गणितीय तत्व को निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य अक्षरों, में फ्रेमिंग के रूप में घेरता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थशास्त्र का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के एक फ़ंक्शन को लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के एक फ़ंक्शन को लेता है। |
| **bool** [get_AlignmentPoint](./get_alignmentpoint/)() override | जब true हो, यह ऑपरेटर एमुलेटर एक संरेखन बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्दिष्ट संरेखन बिंदु इसके साथ संरेखित किए जा सकते हैं। डिफ़ॉल्ट: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | बेस तर्क |
| **bool** [get_Differential](./get_differential/)() override | जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (जैसे, \\uD835\\uDC51\\uD835\\uDC65 इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false |
| **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() override | स्पष्ट ब्रेक यह निर्दिष्ट करता है कि क्या Box ऑब्जेक्ट की शुरुआत में एक लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह पिछले गणितीय पाठ की लाइन में ऑपरेटर की संख्या को निर्दिष्ट करता है जिसे वर्तमान गणितीय पाठ की लाइन के संरेखन बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)। |
| **bool** [get_NoBreak](./get_nobreak/)() override | कोई ब्रेक इस गुण से ऑब्जेक्ट बॉक्स की "अविराम" गुण निर्धारित होती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह कई बाइनरी ऑपरेटरों वाले ऑपरेटर एमुलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true |
| **bool** [get_OperatorEmulator](./get_operatoremulator/)() override | ऑपरेटर एमुलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर के गुण वंशवंत करती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एमुलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | संतान तत्व प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | एक समूहिंग अक्षर, जैसे निचला कर्ली ब्रैकेट या अन्य, का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | समाकलन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | समाकलन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | सीमाओं के बिना समाकलन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | समाकलन लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | समाकलन लेता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
|  [MathBox](./mathbox/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathBox](./) को निर्दिष्ट तत्व के तर्क के रूप में प्रारंभ करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों को क्लोन करना सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक N-ary ऑपरेटर बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | एक N-ary ऑपरेटर बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | इस तत्व के शीर्ष पर एक बार सेट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल निर्धारित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय मूल निर्धारित करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | value type ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग के केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट कम करता है। |
| void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) override | जब true हो, यह ऑपरेटर एमुलेटर एक संरेखन बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्दिष्ट संरेखन बिंदु इसके साथ संरेखित किए जा सकते हैं। डिफ़ॉल्ट: false |
| void [set_Differential](./set_differential/)(**bool**) override | जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (जैसे, \\uD835\\uDC51\\uD835\\uDC65 इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false |
| void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) override | स्पष्ट ब्रेक यह निर्दिष्ट करता है कि क्या Box ऑब्जेक्ट की शुरुआत में एक लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर रैप हो। यह पिछले गणितीय पाठ की लाइन में ऑपरेटर की संख्या को निर्दिष्ट करता है जिसे वर्तमान गणितीय पाठ की लाइन के संरेखन बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)। |
| void [set_NoBreak](./set_nobreak/)(**bool**) override | कोई ब्रेक इस गुण से ऑब्जेक्ट बॉक्स की "अविराम" गुण निर्धारित होती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह कई बाइनरी ऑपरेटरों वाले ऑपरेटर एमुलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true |
| void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) override | ऑपरेटर एमुलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर के गुण वंशवंत करती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एमुलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निचली सीमा लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | निचली सीमा लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सबस्क्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | सबस्क्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सुपरसक्रिप्ट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | सुपरसक्रिप्ट बनाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ऊपरी सीमा लेता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | ऊपरी सीमा लेता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | इस तत्व को एक बॉर्डर-बॉक्स में रखता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | इस तत्व को एक बॉर्डर-बॉक्स में रखता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | एक non-visual बॉक्स (तार्किक समूह) में इस तत्व को रखता है जो समीकरण के घटकों या गणितीय पाठ के अन्य इंस्टेंस को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, चाहे उसमें संरेखन बिंदु हो या न हो, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसे समूह में रखा जा सकता है जिससे भीतर लाइन ब्रेक न हो। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | एक vertical array में रखता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | इस तत्व के नीचे एक बार सेट करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

उदाहरण:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## संबंधित देखें

* क्लास [MathElementBase](../mathelementbase/)
* क्लास [IMathBox](../imathbox/)
* क्लास [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* नेमस्पेस [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)