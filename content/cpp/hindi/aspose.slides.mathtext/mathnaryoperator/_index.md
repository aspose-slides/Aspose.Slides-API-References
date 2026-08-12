---
title: MathNaryOperator
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral। इसमें एक ऑपरेटर, एक बेस (या ऑपरेन्ड), और वैकल्पिक ऊपरी और निचली सीमाएँ शामिल हैं। N-ary ऑपरेटरों के उदाहरण हैं: Summation, Union, Intersection, Integral"
type: docs
weight: 976
url: /hi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator क्लास

Specifies an N-ary mathematical object, such as Summation and Integral. It consists of an operator, a base (or operand), and optional upper and lower limits. Examples of N-ary operators are: Summation, Union, Intersection, Integral

```cpp
class MathNaryOperator : public Aspose::Slides::MathText::MathElementBase,
                         public Aspose::Slides::MathText::IMathNaryOperator,
                         public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में प्रयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में प्रयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में प्रयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क प्रयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क प्रयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंश और निर्दिष्ट हर होते हैं |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंश और निर्दिष्ट हर होते हैं |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | एक गणितीय तत्व को कोष्ठक में घेरता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षरों) में फ्रेमिंग के रूप में घेरता है |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | बेस तर्क |
| **bool** [get_GrowToMatchOperandHeight](./get_growtomatchoperandheight/)() override | ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई से मेल खाने के लिए वर्टिकली बढ़ता है |
| **bool** [get_HideSubscript](./get_hidesubscript/)() override | सबस्क्रिप्ट छुपाएँ |
| **bool** [get_HideSuperscript](./get_hidesuperscript/)() override | सुपरस्क्रिप्ट छुपाएँ |
| [MathLimitLocations](../mathlimitlocations/) [get_LimitLocation](./get_limitlocation/)() override | सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान |
| char16_t [get_Operator](./get_operator/)() override | Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B' |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Subscript](./get_subscript/)() override | एक सबस्क्रिप्ट तर्क निर्दिष्ट करता है जो उदाहरण के लिए, इंटेग्रल के मामले में, नीचे की सीमा निर्धारित करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Superscript](./get_superscript/)() override | एक सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो उदाहरण के लिए, इंटेग्रल के मामले में, ऊपर की सीमा निर्धारित करता है |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | संतान तत्व प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | निचले कर्ली ब्रैकेट या किसी अन्य समूहित अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | इंटीग्रल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इंटीग्रल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | सीमाओं के बिना इंटीग्रल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | इंटीग्रल लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | इंटीग्रल लेता है |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है। C# 'is' ऑपरेटर का समकक्ष |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | एक गणितीय टेक्स्ट को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। इसे सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें |
| [MathNaryOperator](./mathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathNaryOperator](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |
| [MathNaryOperator](./mathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathNaryOperator](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |
| [MathNaryOperator](./mathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathNaryOperator](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक N-ary ऑपरेटर बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | एक N-ary ऑपरेटर बनाता है |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | इस तत्व के शीर्ष पर बार सेट करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्दिष्ट करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्दिष्ट करता है |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करती है |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है |
| void [set_GrowToMatchOperandHeight](./set_growtomatchoperandheight/)(**bool**) override | ऑपरेटर कैरेक्टर अपने ऑपरेण्ड की ऊँचाई से मेल खाने के लिए वर्टिकली बढ़ता है |
| void [set_HideSubscript](./set_hidesubscript/)(**bool**) override | सबस्क्रिप्ट छुपाएँ |
| void [set_HideSuperscript](./set_hidesuperscript/)(**bool**) override | सुपरस्क्रिप्ट छुपाएँ |
| void [set_LimitLocation](./set_limitlocation/)([MathLimitLocations](../mathlimitlocations/)) override | सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान |
| void [set_Operator](./set_operator/)(char16_t) override | Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B' |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निचली सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | निचली सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सुपरस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | सुपरस्क्रिप्ट बनाता है |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ऊपरी सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | ऊपरी सीमा लेता है |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | इस तत्व को एक नॉन-विज़ुअल बॉक्स (लॉजिकल ग्रुपिंग) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय टेक्स्ट के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एलाइनमेंट पॉइंट के साथ या बिना ऑपरेटर एमुलेटर के रूप में, लाइन ब्रेक पॉइंट के रूप में, या इस प्रकार समूहित हो सकता है कि अंदर लाइन ब्रेक न हो |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | एक वर्टिकल एरे में रखता है |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | इस तत्व के नीचे बार सेट करता है |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है |

## टिप्पणी

उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
```

## देखें

* क्लास [MathElementBase](../mathelementbase/)
* क्लास [IMathNaryOperator](../imathnaryoperator/)
* क्लास [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* नामस्थान [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)