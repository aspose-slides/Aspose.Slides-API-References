---
title: ILineFillFormat
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लाइन भरने के लिए गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 2731
url: /hi/aspose.slides/ilinefillformat/
---
## ILineFillFormat क्लास

Lines filling के लिए गुण प्रस्तुत करता है।

```cpp
class ILineFillFormat : public Aspose::Slides::IFillParamSource
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() | फिल प्रकार लौटाता है। पढ़ें [Slides::FillType](../filltype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormat](../igradientformat/)\> [get_GradientFormat](./get_gradientformat/)() | ग्रेडिएंट फ़िल फ़ॉर्मेट लौटाता है। केवल-पठन [IGradientFormat](../igradientformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormat](../ipatternformat/)\> [get_PatternFormat](./get_patternformat/)() | पैटर्न फ़िल फ़ॉर्मेट लौटाता है। केवल-पठन [IPatternFormat](../ipatternformat/)। |
| virtual [NullableBool](../nullablebool/) [get_RotateWithShape](./get_rotatewithshape/)() | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_SolidFillColor](./get_solidfillcolor/)() | सॉलिड फ़िल का रंग लौटाता है। केवल-पठन [IColorFormat](../icolorformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम वस्तुओं का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। प्रत्यक्ष रूप से कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउंट घटाता है। |
| virtual void [set_FillType](./set_filltype/)([Aspose::Slides::FillType](../filltype/)) | फ़िल प्रकार सेट करता है। लिखें [Slides::FillType](../filltype/)। |
| virtual void [set_RotateWithShape](./set_rotatewithshape/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि फ़िल को आकार के साथ घुमाया जाना चाहिए या नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्गुमेंट को एक कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम वस्तुओं को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। प्रत्यक्ष रूप से कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [IFillParamSource](../ifillparamsource/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)