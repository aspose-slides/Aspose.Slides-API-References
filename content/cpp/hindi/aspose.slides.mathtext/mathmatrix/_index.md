---
title: MathMatrix
second_title: Aspose.Slides for C++ API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित चाइल्ड एलिमेंट्स से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलिमिटर नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य तर्कों का उपयोग मैट्रिक्स में अंतराल बनाने के लिए किया जा सकता है।
type: docs
weight: 950
url: /hi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix वर्ग

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित चाइल्ड एलिमेंट्स से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलिमिटर नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट ([IMathDelimiter](../imathdelimiter/)) का उपयोग करना चाहिए। शून्य तर्कों का उपयोग मैट्रिक्स में अंतराल बनाने के लिए किया जा सकता है।

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | एक अभिज्ञापक चिन्ह सेट करता है (इस तत्व के ऊपर स्थित एक अक्षर) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेता है और निर्दिष्ट अतिरिक्त तर्क लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेता है और निर्दिष्ट अतिरिक्त तर्क लेता है |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | निर्धारित स्तम्भ को हटाता है |
| void [DeleteRow](./deleterow/)(**int32_t**) override | निर्धारित पंक्ति को हटाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस अंशांक के साथ और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | इस अंशांक के साथ और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | एक गणितीय तत्व को कोष्ठकों में घेरता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | एक गणितीय तत्व को निर्दिष्ट अक्षरों में घेरता है जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण देता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करते हुए एक तर्क का फ़ंक्शन लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करते हुए एक तर्क का फ़ंक्शन लेता है |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | आसपास के पाठ के संबंध में लंबवत जस्टिफिकेशन निर्दिष्ट करता है। संभावित मान शीर्ष, निचला और मध्य हैं। डिफ़ॉल्ट: मध्य। |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | मैट्रिक्स में स्तम्भों की संख्या |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | मैट्रिक्स के स्तम्भों के बीच क्षैतिज अंतर की मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20वाँ) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में इसे नज़रअंदाज़ किया जाता है। डिफ़ॉल्ट: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | मैट्रिक्स के स्तम्भों के बीच क्षैतिज अंतर का प्रकार; क्षैतिज अंतर की इकाइयाँ ems या पॉइंट्स (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ। डिफ़ॉल्ट: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | टविप्स (बिंदु का 1/20वाँ) में न्यूनतम स्तम्भ चौड़ाई। गैप स्पेसिंग (जिसे \"Column Gap\" या \"Gap Width\" भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स [Column](../../aspose.slides/column/) स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0। |
| **int32_t** [get_RowCount](./get_rowcount/)() override | मैट्रिक्स में पंक्तियों की संख्या |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतर की मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20वाँ) के रूप में व्याख्या किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को अर्ध-रेखाओं के रूप में व्याख्या किया जाता है। डिफ़ॉल्ट: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतर का प्रकार; लंबवत अंतर की इकाइयाँ रेखाएँ या बिंदु (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | संतान तत्व प्राप्त करें |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | निर्धारित स्तम्भ की क्षैतिज संरेखण प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफरेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | इस तत्व को समूहिंग अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके एक समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | मैट्रिक्स का तत्व |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | मैट्रिक्स का तत्व |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | निर्धारित कॉलम के बाद एक नया कॉलम सम्मिलित करता है। नई कॉलम के सभी तत्व प्रारम्भ में null होते हैं। |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | निर्धारित कॉलम से पहले एक नया कॉलम सम्मिलित करता है। नई कॉलम के सभी तत्व प्रारम्भ में null होते हैं। |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | निर्धारित पंक्ति के बाद एक नई पंक्ति सम्मिलित करता है। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं। |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | निर्धारित पंक्ति से पहले एक नई पंक्ति सम्मिलित करता है। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | समाकल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | समाकल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | समाकल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | समाकल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | समाकल लेता है |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है जिससे लॉक होता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
|  [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | [MathMatrix](./) वर्ग का एक नया उदाहरण आरंभ करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समतुल्य। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक N-ary ऑपरेटर बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | एक N-ary ऑपरेटर बनाता है |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | इस तत्व के ऊपर एक बार सेट करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल दर्शाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल दर्शाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | आसपास के पाठ के संबंध में लंबवत जस्टिफिकेशन निर्दिष्ट करता है। संभावित मान शीर्ष, निचला और मध्य हैं। डिफ़ॉल्ट: मध्य। |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | मैट्रिक्स के स्तम्भों के बीच क्षैतिज अंतर की मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20वाँ) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में इसे नज़रअंदाज़ किया जाता है। डिफ़ॉल्ट: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | मैट्रिक्स के स्तम्भों के बीच क्षैतिज अंतर का प्रकार; क्षैतिज अंतर की इकाइयाँ ems या पॉइंट्स (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ। डिफ़ॉल्ट: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | टविप्स (बिंदु का 1/20वाँ) में न्यूनतम स्तम्भ चौड़ाई। गैप स्पेसिंग (जिसे \"Column Gap\" या \"Gap Width\" भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स [Column](../../aspose.slides/column/) स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0। |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतर की मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20वाँ) के रूप में व्याख्या किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को अर्ध-रेखाओं के रूप में व्याख्या किया जाता है। डिफ़ॉल्ट: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतर का प्रकार; लंबवत अंतर की इकाइयाँ रेखाएँ या बिंदु (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | निर्धारित स्तम्भ की क्षैतिज संरेखण सेट करें |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | निर्धारित स्तम्भों की क्षैतिज संरेखण सेट करें |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निचली सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | निचली सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | सुपरस्क्रिप्ट बनाता है |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट तर्क को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | उपरी सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | उपरी सीमा लेता है |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | इस तत्व को एक गैर-चित्रात्मक बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में काम कर सकता है जिसमें या बिना संरेखण बिंदु के, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित हो सकता है कि लाइन ब्रेक की अनुमति न हो। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | एक लंबवत सरणी में रखता है |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | इस तत्व के नीचे एक बार सेट करता है |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## टिप्पणियाँ

Example: 
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## अन्य देखें

* वर्ग [MathElementBase](../mathelementbase/)
* वर्ग [IMathMatrix](../imathmatrix/)
* वर्ग [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* नामस्थान [Aspose::Slides::MathText](../)
* पुस्तकालय [Aspose.Slides](../../)