---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति में एनीमेशन जनरेटर का प्रतिनिधित्व करता है।
type: docs
weight: 612
url: /hi/aspose.slides.export/presentationanimationsgenerator/
---
## PresentationAnimationsGenerator क्लास

[Presentation](../../aspose.slides/presentation/) में एनीमेशन के जेनरेटर का प्रतिनिधित्व करता है।

```cpp
class PresentationAnimationsGenerator : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Dispose](./dispose/)() override | [PresentationAnimationsGenerator](./) का उदाहरण निपटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() const | डिफ़ॉल्ट देरी समय [ms] प्राप्त करता है। |
| **int32_t** [get_ExportedSlides](./get_exportedslides/)() const | निर्यातित स्लाइड्स की संख्या प्राप्त करता है। |
| **bool** [get_IncludeHiddenSlides](./get_includehiddenslides/)() const | छिपी स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
|  [PresentationAnimationsGenerator](./presentationanimationsgenerator/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [PresentationAnimationsGenerator](./) की नई इंस्टेंस बनाता है। |
|  [PresentationAnimationsGenerator](./presentationanimationsgenerator/)([System::Drawing::Size](../../system.drawing/size/)) | [PresentationAnimationsGenerator](./) की नई इंस्टेंस बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Run](./run/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>\>\>) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट्स जेनरेशन चलाता है। |
| void [Run](./run/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>\>\>, **int32_t**, [PresentationPlayer::FrameTickHandler](../presentationplayer/frametickhandler/)) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट्स जेनरेशन चलाता है। |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) | डिफ़ॉल्ट देरी समय [ms] सेट करता है। |
| void [set_IncludeHiddenSlides](./set_includehiddenslides/)(**bool**) | छिपी स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को एक कमजोर पॉइंटर (शेयर किए गए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और 반환 करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

```cpp
void OnFrameTick(System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args)
{
    args->GetFrame()->Save(System::String::Format(u"frame_{0}.png", sender->get_FrameIndex()), System::Drawing::Imaging::ImageFormat::get_Png());
}

void SaveFrames()
{
    const int32_t FPS = 30;

    auto presentation = System::MakeObject<Presentation>(u"animated.pptx");
    auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation);

    auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, FPS);
    player->FrameTick += OnFrameTick;

    animationsGenerator->Run(presentation->get_Slides());
}
```

## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)