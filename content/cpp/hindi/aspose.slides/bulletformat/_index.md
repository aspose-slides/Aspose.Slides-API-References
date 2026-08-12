---
title: BulletFormat
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 248
url: /hi/aspose.slides/bulletformat/
---
## BulletFormat क्लास


पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## विधियाँ

| Method | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | डिफ़ॉल्ट शून्य-से-अधिक शिफ्ट्स को प्रभावी पैराग्राफ **Indent** और **MarginLeft** के लिए सेट करता है जब bullets सक्षम हो (जैसे PowerPoint करता है यदि पैराग्राफ बुलेट्स/नंबरिंग सक्षम किया जाए)। यदि bullets अक्षम हो तो केवल पैराग्राफ **Indent** और **MarginLeft** को रीसेट करता है (जैसे PowerPoint करता है यदि पैराग्राफ बुलेट्स/नंबरिंग अक्षम किया जाए)। इंडेंट शिफ्ट्स को वर्तमान बुलेट कॉन्टेक्स्ट - IBulletFormat::get(set)_Type, .NumberedBulletStyle और प्रथम भाग की **FontHeight** के अनुसार लागू किया जाता है। शून्य-से-अधिक इंडेंट शिफ्ट्स को वर्तमान पैराग्राफ के प्रभावी **Indent** और **MarginLeft** पर लागू किया जाता है (परिणामी मान स्थानीय मान बनते हैं)। |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| char16_t [get_Char](./get_char/)() override | एक पैराग्राफ के बुलेट कैरेक्टर को बिना वारिस के लौटाता है। पढ़ें **wchar_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | एक पैराग्राफ के बुलेट का रंग फ़ॉर्मेट बिना वारिस के लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | एक पैराग्राफ के बुलेट का फ़ॉन्ट बिना वारिस के लौटाता है। पढ़ें [IFontData](../ifontdata/)। |
| **float** [get_Height](./get_height/)() override | एक पैराग्राफ के बुलेट की ऊँचाई को बिना वारिस के लौटाता है। मान std::numeric_limits<float>::quiet_NaN() यह निर्धारित करता है कि बुलेट पैराग्राफ के प्रथम भाग से ऊँचाई विरासत में लेता है। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | निर्धारित करता है कि बुलेट का अपना रंग है या वह पैराग्राफ के प्रथम भाग से विरासत में लेता है। **[NullableBool::True](../nullablebool/)** यदि बुलेट का अपना रंग है और **[NullableBool::False](../nullablebool/)** यदि बुलेट रंग को प्रथम भाग से विरासत में लेता है। पढ़ें [NullableBool](../nullablebool/)। |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या वह पैराग्राफ के प्रथम भाग से विरासत में लेता है। **[NullableBool::True](../nullablebool/)** यदि बुलेट का अपना फ़ॉन्ट है और **[NullableBool::False](../nullablebool/)** यदि बुलेट फ़ॉन्ट को प्रथम भाग से विरासत में लेता है। पढ़ें [NullableBool](../nullablebool/)। |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | बिना वारिस के क्रमांकित बुलेट समूह के लिए प्रयुक्त पहला नंबर लौटाता है। पढ़ें **int16_t**। |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | बिना वारिस के क्रमांकित बुलेट की शैली लौटाता है। पढ़ें [Slides::NumberedBulletStyle](../numberedbulletstyle/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | बिना वारिस के पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर लौटाता है। केवल-पढ़ने योग्य [ISlidesPicture](../islidespicture/)। |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | बिना वारिस के पैराग्राफ के बुलेट प्रकार को लौटाता है। पढ़ें [BulletType](../bullettype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | वारिसी को लागू करके प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रैफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रैफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr स्थिति के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Char](./set_char/)(char16_t) override | बिना वारिस के पैराग्राफ के बुलेट कैरेक्टर को सेट करता है। लिखें **wchar_t**। |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | बिना वारिस के पैराग्राफ के बुलेट फ़ॉन्ट को सेट करता है। लिखें [IFontData](../ifontdata/)। |
| void [set_Height](./set_height/)(**float**) override | बिना वारिस के पैराग्राफ के बुलेट ऊँचाई को सेट करता है। मान std::numeric_limits<float>::quiet_NaN() यह निर्धारित करता है कि बुलेट पैराग्राफ के प्रथम भाग से ऊँचाई विरासत में लेता है। लिखें **float**। |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि बुलेट का अपना रंग है या वह पैराग्राफ के प्रथम भाग से विरासत में लेता है। **[NullableBool::True](../nullablebool/)** यदि बुलेट का अपना रंग है और **[NullableBool::False](../nullablebool/)** यदि बुलेट रंग को प्रथम भाग से विरासत में लेता है। लिखें [NullableBool](../nullablebool/)। |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या वह पैराग्राफ के प्रथम भाग से विरासत में लेता है। **[NullableBool::True](../nullablebool/)** यदि बुलेट का अपना फ़ॉन्ट है और **[NullableBool::False](../nullablebool/)** यदि बुलेट फ़ॉन्ट को प्रथम भाग से विरासत में लेता है। लिखें [NullableBool](../nullablebool/)। |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | बिना वारिस के क्रमांकित बुलेट समूह के लिए प्रयुक्त पहला नंबर सेट करता है। लिखें **int16_t**। |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | बिना वारिस के क्रमांकित बुलेट की शैली सेट करता है। लिखें [Slides::NumberedBulletStyle](../numberedbulletstyle/)। |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | बिना वारिस के पैराग्राफ के बुलेट प्रकार को सेट करता है। लिखें [BulletType](../bullettype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IBulletFormat](../ibulletformat/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)