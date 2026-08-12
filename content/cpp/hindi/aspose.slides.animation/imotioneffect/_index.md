---
title: IMotionEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के मोशन इफ़ेक्ट व्यवहार को दर्शाता है।
type: docs
weight: 287
url: /hi/aspose.slides.animation/imotioneffect/
---
## IMotionEffect क्लास

Represent motion effect behavior of effect.

```cpp
class IMotionEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | निर्दिष्ट करता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | निर्दिष्ट करता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ मिलाया गया है या नहीं। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual **float** [get_Angle](./get_angle/)() | मोशन पाथ के सापेक्ष कोण का विवरण देता है। पढ़ें **float**। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | एनीमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का विवरण देता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | एनीमेशन शुरू करने के लिए x/y कॉऑर्डिनेट (प्रतिशत में) निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() | स्लाइड लेआउट या पैरेंट की तरह, मोशन पाथ की उत्पत्ति किससे सापेक्ष है, इसे निर्दिष्ट करता है। पढ़ें [MotionOriginType](../motionorigintype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() | एनीमेशन मोशन के लिए पाथ प्रिमिटिव और उसके बाद कॉऑर्डिनेट्स को निर्दिष्ट करता है। पढ़ें [IMotionPath](../imotionpath/)। |
| virtual [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() | शेप मूव होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। पढ़ें [MotionPathEditMode](../motionpatheditmode/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | व्यवहार की प्रॉपर्टीज़ को दर्शाता है। केवल-रीड [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले रोटेशन के केंद्र का विवरण देता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ें [ITiming](../itiming/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | एनीमेशन मोशन इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटर ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्दिष्ट करता है कि एनीमेशन व्यवहार संग्रहीत होते हैं या नहीं। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | निर्दिष्ट करता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ मिलाया गया है या नहीं। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual void [set_Angle](./set_angle/)(**float**) | मोशन पाथ के सापेक्ष कोण का विवरण देता है। लिखें **float**। |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनीमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का विवरण देता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनीमेशन शुरू करने के लिए x/y कॉऑर्डिनेट (प्रतिशत में) निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) | स्लाइड लेआउट या पैरेंट की तरह, मोशन पाथ की उत्पत्ति किससे सापेक्ष है, इसे निर्दिष्ट करता है। लिखें [MotionOriginType](../motionorigintype/)। |
| virtual void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) | एनीमेशन मोशन के लिए पाथ प्रिमिटिव और उसके बाद कॉऑर्डिनेट्स को निर्दिष्ट करता है। लिखें [IMotionPath](../imotionpath/)। |
| virtual void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) | शेप मूव होने पर मोशन पाथ कैसे चलता है, इसे निर्दिष्ट करता है। लिखें [MotionPathEditMode](../motionpatheditmode/)। |
| virtual void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) | X कोण द्वारा मोशन पाथ को घुमाने के लिए उपयोग किए जाने वाले रोटेशन के केंद्र का विवरण देता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ को दर्शाता है। लिखें [ITiming](../itiming/)। |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनीमेशन मोशन इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटर ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* Class [IBehavior](../ibehavior/)
* Namespace [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)