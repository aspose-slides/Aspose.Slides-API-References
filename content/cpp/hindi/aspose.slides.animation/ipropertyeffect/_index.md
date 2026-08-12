---
title: IPropertyEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रॉपर्टी इफ़ेक्ट व्यवहार को दर्शाता है।
type: docs
weight: 339
url: /hi/aspose.slides.animation/ipropertyeffect/
---
## IPropertyEffect क्लास

प्रॉपर्टी इफ़ेक्ट व्यवहार को दर्शाता है।

```cpp
class IPropertyEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | एनिमेशन व्यवहारों के संचय को दर्शाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | वर्तमान एनिमेशन व्यवहार अन्य चल रही एनिमेशनों के साथ संयोजित है या नहीं दर्शाता है। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual [System::String](../../system/string/) [get_By](./get_by/)() | एनिमेशन की प्रारम्भ से पहले उसकी स्थिति के संबंध में एनिमेशन के लिए सापेक्ष ऑफ़सेट मान निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| virtual [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() | एनिमेशन के लिए इंटरपोलेशन मोड निर्दिष्ट करता है। पढ़ें [PropertyCalcModeType](../propertycalcmodetype/)। |
| virtual [System::String](../../system/string/) [get_From](./get_from/)() | एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) | निर्दिष्ट सूचकांक पर एनिमेशन का एक बिंदु लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() | एनिमेशन के बिंदुओं को निर्दिष्ट करता है। पढ़ें [IPointCollection](../ipointcollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | व्यवहार की विशेषताओं का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | इफ़ेक्ट व्यवहार के समय संबंधी विशेषताओं का प्रतिनिधित्व करता है। पढ़ें [ITiming](../itiming/)। |
| virtual [System::String](../../system/string/) [get_To](./get_to/)() | एनिमेशन के समाप्ति मान को निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| virtual [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() | प्रॉपर्टी मान का प्रकार निर्दिष्ट करता है। पढ़ें [PropertyValueType](../propertyvaluetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। प्रत्यक्ष रूप से कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | एनिमेशन व्यवहारों के संचय को दर्शाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | वर्तमान एनिमेशन व्यवहार अन्य चल रही एनिमेशनों के साथ संयोजित है या नहीं दर्शाता है। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| virtual void [set_By](./set_by/)([System::String](../../system/string/)) | एनिमेशन की प्रारम्भ से पहले उसकी स्थिति के संदर्भ में सापेक्ष ऑफ़सेट मान निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) | एनिमेशन के लिए इंटरपोलेशन मोड निर्दिष्ट करता है। लिखें [PropertyCalcModeType](../propertycalcmodetype/)। |
| virtual void [set_From](./set_from/)([System::String](../../system/string/)) | एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) | एनिमेशन के बिंदुओं को निर्दिष्ट करता है। लिखें [IPointCollection](../ipointcollection/)। |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। लिखें [ITiming](../itiming/)। |
| virtual void [set_To](./set_to/)([System::String](../../system/string/)) | एनिमेशन का समाप्ति मान निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) | प्रॉपर्टी मान का प्रकार निर्दिष्ट करता है। लिखें [PropertyValueType](../propertyvaluetype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे प्रत्यक्ष रूप से कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे प्रत्यक्ष रूप से कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। प्रत्यक्ष रूप से कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे प्रत्यक्ष रूप से कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे प्रत्यक्ष रूप से कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IBehavior](../ibehavior/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)