---
title: ILineFormat
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: लाइन का स्वरूप दर्शाता है।
type: docs
weight: 2757
url: /hi/aspose.slides/ilineformat/
---
## ILineFormat क्लास

Represents format of a line.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | निर्धारित करता है कि दो [LineFormat](../lineformat/) उदाहरण बराबर हैं या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग हेतु। |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | रेखा संरेखण लौटाता है। पढ़ें [LineAlignment](../linealignment/)। |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | रेखा की शुरुआत में तीर-हेड की लंबाई लौटाता है। पढ़ें [LineArrowheadLength](../linearrowheadlength/)। |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | रेखा की शुरुआत में तीर-हेड शैली लौटाता है। पढ़ें [LineArrowheadStyle](../linearrowheadstyle/)। |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | रेखा की शुरुआत में तीर-हेड की चौड़ाई लौटाता है। पढ़ें [LineArrowheadWidth](../linearrowheadwidth/)। |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | रेखा कैप शैली लौटाता है। पढ़ें [LineCapStyle](../linecapstyle/)। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | कस्टम डैश पैटर्न लौटाता है। पढ़ें **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | रेखा डैश शैली लौटाता है। पढ़ें [LineDashStyle](../linedashstyle/)। |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | रेखा के अंत में तीर-हेड की लंबाई लौटाता है। पढ़ें [LineArrowheadLength](../linearrowheadlength/)। |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | रेखा के अंत में तीर-हेड शैली लौटाता है। पढ़ें [LineArrowheadStyle](../linearrowheadstyle/)। |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | रेखा के अंत में तीर-हेड की चौड़ाई लौटाता है। पढ़ें [LineArrowheadWidth](../linearrowheadwidth/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | रेखा का भराव प्रारूप लौटाता है। केवल पढ़ने योग्य [ILineFillFormat](../ilinefillformat/)। |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | यदि रेखा प्रारूप परिभाषित नहीं है (जैसे अभी बनाया गया, डिफ़ॉल्ट), तो सत्य लौटाता है। केवल पढ़ने योग्य **bool**। |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | रेखाओं के जोड़ शैली लौटाता है। पढ़ें [LineJoinStyle](../linejoinstyle/)। |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | रेखा की मिटर सीमा लौटाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | रेखा की स्केच प्रारूप लौटाता है। केवल पढ़ने योग्य [ISketchFormat](../isketchformat/)। |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | रेखा शैली लौटाता है। पढ़ें [LineStyle](../linestyle/)। |
| virtual **double** [get_Width](./get_width/)() | रेखा की चौड़ाई लौटाता है। पढ़ें **double**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | विरासत लागू करके प्रभावी रेखा फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना द्वारा वैल्यू टाइप ऑब्जेक्ट को nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | रेखा संरेखण सेट करता है। लिखें [LineAlignment](../linealignment/)। |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | रेखा की शुरुआत में तीर-हेड की लंबाई सेट करता है। लिखें [LineArrowheadLength](../linearrowheadlength/)। |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | रेखा की शुरुआत में तीर-हेड शैली सेट करता है। लिखें [LineArrowheadStyle](../linearrowheadstyle/)। |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | रेखा की शुरुआत में तीर-हेड की चौड़ाई सेट करता है। लिखें [LineArrowheadWidth](../linearrowheadwidth/)। |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | रेखा कैप शैली सेट करता है। लिखें [LineCapStyle](../linecapstyle/)। |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | कस्टम डैश पैटर्न सेट करता है। लिखें **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | रेखा डैश शैली सेट करता है। लिखें [LineDashStyle](../linedashstyle/)। |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | रेखा के अंत में तीर-हेड की लंबाई सेट करता है। लिखें [LineArrowheadLength](../linearrowheadlength/)। |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | रेखा के अंत में तीर-हेड शैली सेट करता है। लिखें [LineArrowheadStyle](../linearrowheadstyle/)। |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | रेखा के अंत में तीर-हेड की चौड़ाई सेट करता है। लिखें [LineArrowheadWidth](../linearrowheadwidth/)। |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | रेखाओं के जोड़ शैली सेट करता है। लिखें [LineJoinStyle](../linejoinstyle/)। |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | रेखा की मिटर सीमा सेट करता है। लिखें **float**। |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | रेखा शैली सेट करता है। लिखें [LineStyle](../linestyle/)। |
| virtual void [set_Width](./set_width/)(**double**) | रेखा की चौड़ाई सेट करता है। लिखें **double**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (शेयर्ड नहीं) के रूप में सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [ILineParamSource](../ilineparamsource/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)