---
title: IBulletFormat
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अनुच्छेद बुलेट फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 1561
url: /hi/aspose.slides/ibulletformat/
---
## IBulletFormat वर्ग

Represents paragraph bullet formatting properties.

```cpp
class IBulletFormat : public virtual System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | जब बुलेट्स सक्षम होते हैं (जैसा कि PowerPoint में पैराग्राफ बुलेट्स/नंबरिंग को सक्षम करने पर होता है) तो प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है। यदि बुलेट्स अक्षम हों तो केवल पैराग्राफ Indent और MarginLeft को रीसेट करता है (जैसा कि PowerPoint में पैराग्राफ बुलेट्स/नंबरिंग को अक्षम करने पर होता है)। Indent शिफ्ट्स वर्तमान बुलेट कॉन्टेक्स्ट - IBulletFormat::get(set)_Type, .NumberedBulletStyle और पहले हिस्से के FontHeight के सन्दर्भ में लागू होते हैं। गैर-शून्य Indent शिफ्ट्स वर्तमान पैराग्राफ के प्रभावी Indent और MarginLeft पर लागू होते हैं (परिणामी मान स्थानीय मान बनाते हैं)। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual char16_t [get_Char](./get_char/)() | एक पैराग्राफ का बुलेट अक्षर बिना इनहेरिटेंस के वापस करता है। पढ़ें **wchar_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | एक पैराग्राफ के बुलेट का रंग फ़ॉर्मेट बिना इनहेरिटेंस के वापस करता है। केवल-पढ़ने योग्य [IColorFormat](../icolorformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | एक पैराग्राफ के बुलेट फ़ॉन्ट को बिना इनहेरिटेंस के वापस करता है। पढ़ें [IFontData](../ifontdata/)। |
| virtual **float** [get_Height](./get_height/)() | एक पैराग्राफ के बुलेट की ऊँचाई बिना इनहेरिटेंस के वापस करता है। मान std::numeric_limits<float>::quiet_NaN() निर्धारित करता है कि बुलेट पैराग्राफ के पहले हिस्से से ऊँचाई इनहेरिट करता है। पढ़ें **float**। |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से इनहेरिट करता है। यदि बुलेट का अपना रंग है तो **[NullableBool::True](../nullablebool/)**, और यदि बुलेट रंग को पहले हिस्से से इनहेरिट करता है तो **[NullableBool::False](../nullablebool/)**। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से इनहेरिट करता है। यदि बुलेट का अपना फ़ॉन्ट है तो **[NullableBool::True](../nullablebool/)**, और यदि बुलेट फ़ॉन्ट को पहले हिस्से से इनहेरिट करता है तो **[NullableBool::False](../nullablebool/)**। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | बिना इनहेरिटेंस के क्रमांकित बुलेट्स समूह के लिए उपयोग की जाने वाली प्रथम संख्या वापस करता है। पढ़ें **int16_t**। |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | बिना इनहेरिटेंस के क्रमांकित बुलेट की शैली वापस करता है। पढ़ें [NumberedBulletStyle](../numberedbulletstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | एक पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर बिना इनहेरिटेंस के वापस करता है। केवल-पढ़ने योग्य [ISlidesPicture](../islidespicture/)। |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | एक पैराग्राफ के बुलेट प्रकार को बिना इनहेरिटेंस के वापस करता है। पढ़ें [BulletType](../bullettype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | इनहेरिटेंस लागू होने पर प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफरेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| virtual void [set_Char](./set_char/)(char16_t) | बिना इनहेरिटेंस के पैराग्राफ का बुलेट अक्षर सेट करता है। लिखें **wchar_t**। |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | बिना इनहेरिटेंस के पैराग्राफ का बुलेट फ़ॉन्ट सेट करता है। लिखें [IFontData](../ifontdata/)। |
| virtual void [set_Height](./set_height/)(**float**) | बिना इनहेरिटेंस के पैराग्राफ का बुलेट ऊँचाई सेट करता है। मान std::numeric_limits<float>::quiet_NaN() निर्धारित करता है कि बुलेट पैराग्राफ के पहले हिस्से से ऊँचाई इनहेरिट करता है। लिखें **float**। |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से इनहेरिट करता है। यदि बुलेट का अपना रंग है तो **[NullableBool::True](../nullablebool/)**, और यदि बुलेट रंग को पहले हिस्से से इनहेरिट करता है तो **[NullableBool::False](../nullablebool/)**। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से इनहेरिट करता है। यदि बुलेट का अपना फ़ॉन्ट है तो **[NullableBool::True](../nullablebool/)**, और यदि बुलेट फ़ॉन्ट को पहले हिस्से से इनहेरिट करता है तो **[NullableBool::False](../nullablebool/)**। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | बिना इनहेरिटेंस के क्रमांकित बुलेट समूह के लिए उपयोग की जाने वाली प्रथम संख्या सेट करता है। लिखें **int16_t**। |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | बिना इनहेरिटेंस के क्रमांकित बुलेट की शैली सेट करता है। लिखें [NumberedBulletStyle](../numberedbulletstyle/)। |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | बिना इनहेरिटेंस के पैराग्राफ का बुलेट प्रकार सेट करता है। लिखें [BulletType](../bullettype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* वर्ग [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)