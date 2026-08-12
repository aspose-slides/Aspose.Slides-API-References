---
title: IMathBox
second_title: Aspose.Slides for C++ API संदर्भ
description: गणितीय तत्व की तार्किक बॉक्सिंग (पैकेजिंग) निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स किया गया वस्तु ऑपरेटर इम्यूलेटर के रूप में काम कर सकता है चाहे उसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इसे इस तरह समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के रूप में, \"==\" ऑपरेटर को लाइन ब्रेक को रोकने के लिए बॉक्स किया जाना चाहिए।
type: docs
weight: 170
url: /hi/aspose.slides.mathtext/imathbox/
---
## IMathBox क्लास

गणितीय तत्व की तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स किया गया वस्तु ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है चाहे उसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसे समूहित हो सकता है जिससे भीतर लाइन ब्रेक न हो सके। उदाहरण के लिए, \"==\" ऑपरेटर को लाइन ब्रेक को रोकने के लिए बॉक्स किया जाना चाहिए।

```cpp
class IMathBox : public virtual Aspose::Slides::MathText::IMathElement
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | एक उच्चारण चिह्न सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | निर्दिष्ट प्रकार की एक भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | एक गणितीय तत्व को कोष्ठकों में संलग्न करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | इस तत्व को निर्दिष्ट वर्णों में संलग्न करता है जैसे कि कोष्ठक या अन्य वर्ण फ्रेमिंग के रूप में |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| virtual **bool** [get_AlignmentPoint](./get_alignmentpoint/)() | जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | आधार तर्क |
| virtual **bool** [get_Differential](./get_differential/)() | डिफरेंशियल। जब सत्य हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदा., \\uD835\\uDC51\\uD835\\uDC65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उचित क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false |
| virtual **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() | स्पष्ट विराम यह निर्दिष्ट करता है कि क्या बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स वस्तु की शुरुआत पर ही रैप हो। यह उस ऑपरेटर की संख्या निर्दिष्ट करता है जो पूर्व पंक्ति के गणितीय पाठ में है और वर्तमान पंक्ति के गणितीय पाठ के लिए संरेखण बिंदु के रूप में उपयोग होगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट विराम नहीं) |
| virtual **bool** [get_NoBreak](./get_nobreak/)() | कोई विराम नहीं। यह गुण वस्तु बॉक्स पर \"अविभाज्य\" गुण निर्दिष्ट करता है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटर्स के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से मिलकर बनते हैं। जब यह तत्व निर्दिष्ट नहीं है, तो बॉक्स के भीतर विराम हो सकते हैं। डिफ़ॉल्ट: true |
| virtual **bool** [get_OperatorEmulator](./get_operatoremulator/)() | ऑपरेटर इम्यूलेटर। जब सत्य हो, बॉक्स और इसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर के गुण विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर्स अक्सर तब उपयोग होते हैं जब एक या अधिक ग्लिफ़ मिलकर '==' जैसे ऑपरेटर बनाते हैं। डिफ़ॉल्ट मान: false |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | सन्तान तत्व प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समान रूप। कस्टम वस्तुओं का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान रूप। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | नीचे की कर्ली ब्रैकेट या अन्य समूहित वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | समाकलन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | समाकलन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | सीमा बिना समाकलन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | समाकलन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | समाकलन लेता है |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान रूप। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है जो लॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समान रूप। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | एक N-री ऑपरेटर बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | एक N-री ऑपरेटर बनाता है |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | इस तत्व के शीर्ष पर बार सेट करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निर्दिष्ट तर्क से दिए गए घात का गणितीय मूल निर्दिष्ट करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | निर्दिष्ट तर्क से दिए गए घात का गणितीय मूल निर्दिष्ट करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू प्रकार की वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) | जब सत्य हो, यह ऑपरेटर इम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false |
| virtual void [set_Differential](./set_differential/)(**bool**) | डिफरेंशियल। जब सत्य हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (उदा., \\uD835\\uDC51\\uD835\\uDC65 एक इंटेग्रैंड में), और गणितीय डिफरेंशियल के लिए उचित क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false |
| virtual void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) | स्पष्ट विराम यह निर्दिष्ट करता है कि क्या बॉक्स वस्तु की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स वस्तु की शुरुआत पर ही रैप हो। यह उस ऑपरेटर की संख्या निर्दिष्ट करता है जो पूर्व पंक्ति के गणितीय पाठ में है और वर्तमान पंक्ति के गणितीय पाठ के लिए संरेखण बिंदु के रूप में उपयोग होगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट विराम नहीं) |
| virtual void [set_NoBreak](./set_nobreak/)(**bool**) | कोई विराम नहीं। यह गुण वस्तु बॉक्स पर \"अविभाज्य\" गुण निर्दिष्ट करता है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटर्स के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से मिलकर बनते हैं। जब यह तत्व निर्दिष्ट नहीं है, तो बॉक्स के भीतर विराम हो सकते हैं। डिफ़ॉल्ट: true |
| virtual void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) | ऑपरेटर इम्यूलेटर। जब सत्य हो, बॉक्स और इसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर के गुण विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित हो सकता है। ऑपरेटर इम्यूलेटर्स अक्सर तब उपयोग होते हैं जब एक या अधिक ग्लिफ़ मिलकर '==' जैसे ऑपरेटर बनाते हैं। डिफ़ॉल्ट मान: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निचली सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | निचली सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | सबस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | सबस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | बाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | बाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | दाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | दाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | सुपरस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | सुपरस्क्रिप्ट बनाता है |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को सुदृढ़ (shared) के बजाय weak पॉइंटर सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ऊपरी सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | ऊपरी सीमा लेता है |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](./)\> [ToBox](../imathelement/tobox/)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिए किया जाता है। एक बॉक्स किया हुआ वस्तु (उदाहरण के लिए) ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है चाहे उसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसे समूहित हो सकता है जिससे भीतर लाइन ब्रेक न हो सके। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | एक लंबवत सरणी में रखता है |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समान रूप। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | इस तत्व के नीचे एक बार सेट करता है |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
```

## संबंधी देखें

* क्लास [IMathElement](../imathelement/)
* नेमस्पेस [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)