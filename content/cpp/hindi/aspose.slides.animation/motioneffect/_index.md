---
title: MotionEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के गति प्रभाव व्यवहार को दर्शाता है।
type: docs
weight: 469
url: /hi/aspose.slides.animation/motioneffect/
---
## MotionEffect क्लास


प्रभाव के गति प्रभाव व्यवहार को दर्शाता है।

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | यह दर्शाता है कि क्या एनीमेशन व्यवहार संचित होते हैं। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | यह दर्शाता है कि क्या वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ संयोजित है। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| **float** [get_Angle](./get_angle/)() override | गतिशील पथ का सापेक्ष कोण वर्णन करता है। पढ़ें **float**। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | एनीमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | एनीमेशन शुरू करने के लिए x/y समन्वय (प्रतिशत में) निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | निर्दिष्ट करता है कि गतिशील पथ का मूल क्या है, जैसे स्लाइड का लेआउट या पैरेंट, सापेक्ष रूप से। पढ़ें [MotionOriginType](../motionorigintype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | एनीमेशन गति के लिए समन्वयों के साथ अनुक्रमित पथ प्रिमिटिव निर्दिष्ट करता है। पढ़ें [IMotionPath](../imotionpath/)। |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | आकार के स्थानांतरित होने पर गतिशील पथ कैसे चलता है, यह निर्दिष्ट करता है। पढ़ें [MotionPathEditMode](../motionpatheditmode/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | व्यवहार की गुणधर्मों को दर्शाता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | X कोण द्वारा गतिशील पथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन के केंद्र का वर्णन करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | प्रभाव व्यवहार के समय गुणधर्म दर्शाता है। पढ़ें [ITiming](../itiming/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | एनीमेशन गति प्रभाव के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड के समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल के समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है। C# 'is' ऑपरेटर के समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड के समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | यह दर्शाता है कि एनीमेशन व्यवहार संचित होते हैं। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | यह दर्शाता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ संयोजित है। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| void [set_Angle](./set_angle/)(**float**) override | गतिशील पथ का सापेक्ष कोण वर्णन करता है। लिखें **float**। |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनीमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनीमेशन शुरू करने के लिए x/y समन्वय (प्रतिशत में) निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | निर्दिष्ट करता है कि गतिशील पथ का मूल क्या है, जैसे स्लाइड का लेआउट या पैरेंट, सापेक्ष रूप से। लिखें [MotionOriginType](../motionorigintype/)। |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | एनीमेशन गति के लिए समन्वयों के साथ अनुक्रमित पथ प्रिमिटिव निर्दिष्ट करता है। लिखें [IMotionPath](../imotionpath/)। |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | आकार के स्थानांतरित होने पर गतिशील पथ कैसे चलता है, यह निर्दिष्ट करता है। लिखें [MotionPathEditMode](../motionpatheditmode/)। |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | X कोण द्वारा गतिशील पथ को घुमाने के लिए उपयोग किए जाने वाले घूर्णन के केंद्र का वर्णन करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | प्रभाव व्यवहार के समय गुणधर्म दर्शाता है। लिखें [ITiming](../itiming/)। |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनीमेशन गति प्रभाव के लिए लक्ष्य स्थान (प्रतिशत में) निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड के समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Behavior](../behavior/)
* क्लास [IMotionEffect](../imotioneffect/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)