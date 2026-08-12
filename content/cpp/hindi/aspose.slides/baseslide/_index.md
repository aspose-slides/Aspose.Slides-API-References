---
title: BaseSlide
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
type: docs
weight: 170
url: /hi/aspose.slides/baseslide/
---
## BaseSlide क्लास


सभी स्लाइड प्रकारों के लिए सामान्य डेटा को दर्शाता है।

```cpp
class BaseSlide : public virtual Aspose::Slides::IBaseSlide,
                  public Aspose::Slides::IDOMObject,
                  public Aspose::Slides::IStyleColorOwner
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | यह निर्धारित करता है कि दो [IBaseSlide](../ibaseslide/) इंस्टेंस बराबर हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड बराबर मानी जाती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि बराबर हों। तुलना में अनन्य पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे Date [Placeholder](../placeholder/) में वर्तमान तिथि मान, को ध्यान नहीं दिया जाता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) override | निर्दिष्ट वैकल्पिक पाठ वाले आकृति की पहली उत्पत्ति को खोजता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() override | स्लाइड की पृष्ठभूमि लौटाता है। केवल- पढ़ा जा सकता है [IBackground](../ibackground/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर ActiveX नियंत्रण लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() override | स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है। केवल- पढ़ा जा सकता है [IControlCollection](../icontrolcollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | स्लाइड का कस्टम डेटा लौटाता है। केवल- पढ़ा जा सकता है [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल- पढ़ा जा सकता है [IHyperlinkQueries](../ihyperlinkqueries/)। |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | एक स्लाइड का नाम लौटाता है। पढ़ा [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | [IPresentation](../ipresentation/) इंटरफ़ेस लौटाता है। केवल- पढ़ा जा सकता है [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर आकृति लौटाता है। केवल- पढ़ा जा सकता है [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | स्लाइड की आकृतियों को लौटाता है। केवल- पढ़ा जा सकता है [IShapeCollection](../ishapecollection/)। |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। स्वयं मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। पढ़ें **bool**। |
| **uint32_t** [get_SlideId](./get_slideid/)() override | स्लाइड का ID लौटाता है। केवल- पढ़ा जा सकता है **uint32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() override | ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है। केवल- पढ़ा जा सकता है [ISlideShowTransition](../islideshowtransition/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() override | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल- पढ़ा जा सकता है [IAnimationTimeLine](../ianimationtimeline/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | सभी अनुच्छेदों और सभी स्वीकार्य आकृतियों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | सभी अनुच्छेदों और सभी स्वीकार्य आकृतियों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है मूल्य प्रकार ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | स्लाइड का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर सेट करता है (साझा के बजाय)। कंटरनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संदर्भ देखें

* क्लास [IBaseSlide](../ibaseslide/)
* क्लास [IDOMObject](../idomobject/)
* क्लास [IStyleColorOwner](../istylecolorowner/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)