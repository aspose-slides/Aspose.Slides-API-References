---
title: IScaleEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: एनिमेशन स्केल इफ़ेक्ट को दर्शाता है।
type: docs
weight: 365
url: /hi/aspose.slides.animation/iscaleeffect/
---
## IScaleEffect क्लास

एनिमेशन स्केल इफ़ेक्ट को दर्शाता है।

```cpp
class IScaleEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | एनिमेशन व्यवहारों के संचय को दर्शाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | वर्तमान एनिमेशन व्यवहार की अन्य चल रहे एनिमेशनों के साथ संयोजन को दर्शाता है। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | एनिमेशन शुरू करने के लिए x/y समन्वय (प्रतिशत में) निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | व्यवहार की विशेषताओं को दर्शाता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | इफ़ेक्ट व्यवहार के समय संबंधी गुणों को दर्शाता है। पढ़ें [ITiming](../itiming/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | एनिमेशन स्केल इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ZoomContent](./get_zoomcontent/)() | निर्धारित करता है कि सामग्री को ज़ूम किया जाना चाहिए या नहीं। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण दर्शाता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नलपॉइंट के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | एनिमेशन व्यवहारों के संचय को दर्शाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | वर्तमान एनिमेशन व्यवहार की अन्य चल रहे एनिमेशनों के साथ संयोजन को दर्शाता है। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनिमेशन के सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनिमेशन शुरू करने के लिए x/y समन्वय (प्रतिशत में) निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | इफ़ेक्ट व्यवहार के समय संबंधी गुणों को दर्शाता है। लिखें [ITiming](../itiming/)। |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | एनिमेशन स्केल इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_ZoomContent](./set_zoomcontent/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्धारित करता है कि सामग्री को ज़ूम किया जाना चाहिए या नहीं। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्गुमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइस्टर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉक्सिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IBehavior](../ibehavior/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)