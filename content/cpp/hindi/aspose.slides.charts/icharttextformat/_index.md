---
title: IChartTextFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट प्रतिबंधित टेक्स्ट फ़ॉर्मेट गुणों के सेट के साथ कार्य करता है। IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat इंटरफ़ेस इस प्रतिबंधित सेट का वर्णन करते हैं।
type: docs
weight: 898
url: /hi/aspose.slides.charts/icharttextformat/
---
## IChartTextFormat वर्ग


[Chart](../chart/) operate with restricted set of text format properties. [IChartTextFormat](./), [IChartTextBlockFormat](../icharttextblockformat/), [IChartParagraphFormat](../ichartparagraphformat/), [IChartPortionFormat](../ichartportionformat/) interfaces describe this restricted set.

```cpp
class IChartTextFormat : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>) | निर्दिष्ट टेक्स्ट फ्रेम से टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
| virtual void [CopyTo](./copyto/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>) | निर्दिष्ट टेक्स्ट फ्रेम में टेक्स्ट फ़ॉर्मेट कॉपी करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आन्तरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartParagraphFormat](../ichartparagraphformat/)\> [get_ParagraphFormat](./get_paragraphformat/)() | पैराग्राफ फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartParagraphFormat](../ichartparagraphformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPortionFormat](../ichartportionformat/)\> [get_PortionFormat](./get_portionformat/)() | पोर्शन फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartPortionFormat](../ichartportionformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextBlockFormat](../icharttextblockformat/)\> [get_TextBlockFormat](./get_textblockformat/)() | चार्ट टेक्स्ट एलिमेंट्स के लिए फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextBlockFormat](../icharttextblockformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समरूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंज़ है या नहीं। C# ‘is’ ऑपरेटर का समरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समरूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आन्तरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आन्तरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)