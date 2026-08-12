---
title: Backdrop3DScene
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्लेन को परिभाषित करता है जिसमें ग्लो और शैडो जैसे प्रभाव उस आकार के सापेक्ष लागू होते हैं जिसपर इन्हें लागू किया जा रहा है।
type: docs
weight: 92
url: /hi/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene वर्ग

Defines a plane in which effects, such as glow and shadow, are applied in relation to the shape they are being applied to.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## विधियाँ

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | 3D स्थान में एक बिंदु लौटाता है। यह बिंदु वह स्थान है जो बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | एक सामान्य वेक्टर लौटाता है। अधिक सटीक रूप से, यह गुण बैकड्रॉप प्लेन के चेहरे के प्रति लंबवत एक वेक्टर को परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate वस्तु लौटाता है। केवल-पढ़नेयोग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़नेयोग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | ऊपर की दिशा दर्शाने वाला वेक्टर लौटाता है। अधिक सटीक रूप से, यह गुण बैकड्रॉप प्लेन के चेहरे के संदर्भ में ऊपर की दिशा दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ा रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | value प्रकार की वस्तु की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स मामले के लिए विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | 3D स्थान में एक बिंदु निर्धारित करता है। यह बिंदु वह स्थान है जो बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। लिखें **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | एक सामान्य वेक्टर निर्धारित करता है। अधिक सटीक रूप से, यह गुण बैकड्रॉप प्लेन के चेहरे के प्रति लंबवत वेक्टर को परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। लिखें **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | ऊपर की दिशा दर्शाने वाला वेक्टर निर्धारित करता है। अधिक सटीक रूप से, यह गुण बैकड्रॉप प्लेन के चेहरे के संदर्भ में ऊपर की दिशा दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। लिखें **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [PVIObject](../pviobject/)
* वर्ग [IBackdrop3DScene](../ibackdrop3dscene/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)