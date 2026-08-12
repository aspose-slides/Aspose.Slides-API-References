---
title: MathFunction
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक तर्क का फ़ंक्शन निर्दिष्ट करता है।
type: docs
weight: 859
url: /hi/aspose.slides.mathtext/mathfunction/
---
## MathFunction क्लास

एक तर्क का फ़ंक्शन निर्दिष्ट करता है।

```cpp
class MathFunction : public Aspose::Slides::MathText::MathElementBase,
                     public Aspose::Slides::MathText::IMathFunction,
                     public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | एक एक्सेंट मार्क सेट करता है (यह तत्व के शीर्ष पर एक अक्षर) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन लेता है जिसका उपयोग यह इंस्टेंस तर्क के रूप में करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसका उपयोग यह इंस्टेंस तर्क के रूप में करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसका उपयोग यह इंस्टेंस तर्क के रूप में करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | निर्दिष्ट फ़ंक्शन लेता है जिसका उपयोग यह इंस्टेंस तर्क के रूप में करता है और अतिरिक्त तर्क लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | निर्दिष्ट फ़ंक्शन लेता है जिसका उपयोग यह इंस्टेंस तर्क के रूप में करता है और अतिरिक्त तर्क लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | गणितीय तत्व को कोष्ठक में घेरता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में गणितीय तत्व को फ्रेम करता है |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | फ़ंक्शन तर्क |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Name](./get_name/)() override | फ़ंक्शन नाम उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | संतान तत्व प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | नीचे की कर्ली ब्रैकेट या अन्य समूह अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | समाकलन लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | समाकलन लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | सीमाओं के बिना समाकलन लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | समाकलन लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | समाकलन लेता है |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | लक्ष्य प्रकार द्वारा वर्णित प्रकार के इंस्टेंस का प्रतिनिधित्व करता है या नहीं जांचता है। C# 'is' ऑपरेटर का समानांतर। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
|  [MathFunction](./mathfunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathFunction](./) क्लास का नया इंस्टेंस प्रारंभ करता है। |
|  [MathFunction](./mathfunction/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathFunction](./) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | N-ary ऑपरेटर बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | N-ary ऑपरेटर बनाता है |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | दिए गए डिग्री की गणितीय मूल निर्दिष्ट तर्क से निर्दिष्ट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | दिए गए डिग्री की गणितीय मूल निर्दिष्ट तर्क से निर्दिष्ट करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और नलपॉइंट के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | न्यूनतम सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | न्यूनतम सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | सबस्क्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | सुपरसक्रिप्ट बनाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | सुपरसक्रिप्ट बनाता है |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर सेट करता है (शेयर किए गए के बजाय)। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ऊपर की सीमा लेता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | ऊपर की सीमा लेता है |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए गए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए गए रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए गए रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | इस तत्व को एक गैर-विद्युत बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | एक वर्टिकल ऐरे में रखता है |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | इस तत्व के नीचे एक बार सेट करता है |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणियाँ

उदाहरण: 
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## देखें

* क्लास [MathElementBase](../mathelementbase/)
* क्लास [IMathFunction](../imathfunction/)
* क्लास [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* नेमस्पेस [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)