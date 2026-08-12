---
title: PropertyEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रॉपर्टी इफ़ेक्ट व्यवहार को दर्शाता है।
type: docs
weight: 521
url: /hi/aspose.slides.animation/propertyeffect/
---
## PropertyEffect क्लास

प्रॉपर्टी इफ़ेक्ट व्यवहार का प्रतिनिधित्व करता है।

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | निर्देशित करता है कि एनीमेशन व्यवहार संचित हैं या नहीं। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | निर्देशित करता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ संयोजित है या नहीं। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| [System::String](../../system/string/) [get_By](./get_by/)() override | एनीमेशन की स्थिति के पहले के स्थान के सापेक्ष एक सापेक्ष ऑफ़सेट मान निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | एनीमेशन के लिए इंटरपोलेशन मोड निर्दिष्ट करता है। पढ़ें [PropertyCalcModeType](../propertycalcmodetype/)। |
| [System::String](../../system/string/) [get_From](./get_from/)() override | एनीमेशन का प्रारंभिक मान निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर एनीमेशन का बिंदु लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | एनीमेशन के बिंदुओं को निर्दिष्ट करता है। पढ़ें [IPointCollection](../ipointcollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | व्यवहार की प्रॉपर्टीज़ का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ें [ITiming](../itiming/)। |
| [System::String](../../system/string/) [get_To](./get_to/)() override | एनीमेशन के अंतिम मान को निर्दिष्ट करता है। पढ़ें [System::String](../../system/string/)। |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | प्रॉपर्टी वैल्यू के प्रकार को निर्दिष्ट करता है। पढ़ें [PropertyValueType](../propertyvaluetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचें कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | निर्देशित करता है कि एनीमेशन व्यवहार संचित हैं या नहीं। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | निर्देशित करता है कि वर्तमान एनीमेशन व्यवहार अन्य चल रहे एनीमेशन के साथ संयोजित है या नहीं। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | एनीमेशन की स्थिति के पहले के स्थान के सापेक्ष एक सापेक्ष ऑफ़सेट मान निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | एनीमेशन के इंटरपोलेशन मोड को निर्दिष्ट करता है। लिखें [PropertyCalcModeType](../propertycalcmodetype/)। |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | एनीमेशन का प्रारंभिक मान निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | एनीमेशन के बिंदुओं को निर्दिष्ट करता है। लिखें [IPointCollection](../ipointcollection/)। |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। लिखें [ITiming](../itiming/)। |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | एनीमेशन के अंतिम मान को निर्दिष्ट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | प्रॉपर्टी वैल्यू के प्रकार को निर्दिष्ट करता है। लिखें [PropertyValueType](../propertyvaluetype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को वैक-pointer (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें भी

* क्लास [Behavior](../behavior/)
* क्लास [IPropertyEffect](../ipropertyeffect/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)