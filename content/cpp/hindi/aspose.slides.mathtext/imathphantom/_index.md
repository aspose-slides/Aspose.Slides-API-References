---
title: IMathPhantom
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक phantom गणित वस्तु (<m:phant>) का प्रतिनिधित्व करता है जो अपने चाइल्ड एलिमेंट की लेआउट को प्रभावित करता है बिना आवश्यक रूप से इसे प्रदर्शित किए। एक phantom अपने बेस एक्सप्रेशन को छिपा सकता है जबकि इसकी चौड़ाई, ऊँचाई, या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित होते हैं।"
type: docs
weight: 482
url: /hi/aspose.slides.mathtext/imathphantom/
---
## IMathPhantom क्लास


एक phantom गणित वस्तु (<m:phant>) का प्रतिनिधित्व करता है जो अपने चाइल्ड एलिमेंट की लेआउट को प्रभावित करती है बिना आवश्यक रूप से इसे प्रदर्शित किए। एक phantom अपने बेस एक्सप्रेशन को छिपा सकती है जबकि इसकी चौड़ाई, ऊँचाई, या गहराई को संरक्षित रखती है ताकि फ़ॉर्मूले संरेखित हों या स्थान आरक्षित रहे। दृश्यमानता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

```cpp
class IMathPhantom : public virtual Aspose::Slides::MathText::IMathElement
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक कैरेक्टर) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निर्दिष्ट फ़ंक्शन लेता है जो इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | निर्दिष्ट फ़ंक्शन लेता है जो इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | निर्दिष्ट फ़ंक्शन लेता है जो इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निर्दिष्ट फ़ंक्शन लेता है जो इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट को भी लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | निर्दिष्ट फ़ंक्शन लेता है जो इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट को भी लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ़्रैक्शन बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ़्रैक्शन बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | निर्दिष्ट प्रकार का फ़्रैक्शन इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | निर्दिष्ट प्रकार का फ़्रैक्शन इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | गणितीय तत्व को कोष्ठकों में घेरता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | इस तत्व को निर्दिष्ट कैरेक्टर्स (जैसे कोष्ठक या अन्य कैरेक्टर्स) में फ्रेम के रूप में घेरता है |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | बेस आर्ग्युमेंट |
| virtual **bool** [get_Show](./get_show/)() | एक मान प्राप्त करता है जो दर्शाता है कि बेस एलिमेंट प्रदर्शित है या नहीं। |
| virtual **bool** [get_Transp](./get_transp/)() | एक मान प्राप्त करता है जो दर्शाता है कि phantom क्लास-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं। |
| virtual **bool** [get_ZeroAsc](./get_zeroasc/)() | एक मान प्राप्त करता है जो दर्शाता है कि बेस एलिमेंट की एसेंट (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं। |
| virtual **bool** [get_ZeroDesc](./get_zerodesc/)() | एक मान प्राप्त करता है जो दर्शाता है कि बेस एलिमेंट की डीसेंट (बेसलाइन के नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं। |
| virtual **bool** [get_ZeroWidth](./get_zerowidth/)() | एक मान प्राप्त करता है जो दर्शाता है कि बेस एलिमेंट की चौड़ाई को शून्य माना जाना चाहिए या नहीं। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | बच्चे तत्व प्राप्त करें |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | एक बॉटम कर्ली ब्रैकट का उपयोग करके इस तत्व को एक समूह में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | बॉटम कर्ली ब्रैकट या अन्य ग्रुपिंग कैरेक्टर का उपयोग करके इस तत्व को एक समूह में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | इंटीग्रल लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | इंटीग्रल लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | इंटीग्रल लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | इंटीग्रल लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | इंटीग्रल लेता है |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | गणितीय टेक्स्ट को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | एक N-ary ऑपरेटर बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | एक N-ary ऑपरेटर बनाता है |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | इस तत्व के शीर्ष पर बार सेट करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निर्दिष्ट डिग्री के गणितीय मूल को निर्दिष्ट आर्ग्युमेंट से निर्धारित करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | निर्दिष्ट डिग्री के गणितीय मूल को निर्दिष्ट आर्ग्युमेंट से निर्धारित करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Show](./set_show/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि बेस एलिमेंट प्रदर्शित है या नहीं। |
| virtual void [set_Transp](./set_transp/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि phantom क्लास-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं। |
| virtual void [set_ZeroAsc](./set_zeroasc/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि बेस एलिमेंट की एसेंट (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं। |
| virtual void [set_ZeroDesc](./set_zerodesc/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि बेस एलिमेंट की डीसेंट (बेसलाइन के नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं। |
| virtual void [set_ZeroWidth](./set_zerowidth/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि बेस एलिमेंट की चौड़ाई को शून्य माना जाना चाहिए या नहीं। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | निचली सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | निचली सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | सबस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | सबस्क्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | सुपरसक्रिप्ट बनाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | सुपरसक्रिप्ट बनाता है |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेअर्ड के बजाय) सेट करें। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ऊपरी सीमा लेता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | ऊपरी सीमा लेता है |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | इस तत्व को नॉन-विज़ुअल बॉक्स (तार्किक ग्रुपिंग) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है चाहे उसमें अलाइनमेंट पॉइंट हो या न हो, लाइन ब्रेक पॉइंट के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | वर्टिकल ऐरे में रखता है |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | इस तत्व के नीचे बार सेट करता है |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणी


Example: 
```cpp
System::SharedPtr<IMathPhantom> phantom = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"1/2"));
phantom->set_Show(false); // सामग्री को छिपाएँ
phantom->set_ZeroWidth(false); // चौड़ाई को बनाए रखें
```

## देखें

* क्लास [IMathElement](../imathelement/)
* नेमस्पेस [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)