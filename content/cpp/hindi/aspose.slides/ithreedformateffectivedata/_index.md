---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्थिर ऑब्जेक्ट जो प्रभावी 3-D फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 4174
url: /hi/aspose.slides/ithreedformateffectivedata/
---
## IThreeDFormatEffectiveData क्लास

Immutable object जो प्रभावी 3-D फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करती है।

```cpp
class IThreeDFormatEffectiveData : public Aspose::Slides::IThreeDParamSource
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली वाला फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली वाला फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelBottom](./get_bevelbottom/)() | नीचे के 3D बीवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../ishapebeveleffectivedata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelTop](./get_beveltop/)() | ऊपर के 3D बीवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../ishapebeveleffectivedata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICameraEffectiveData](../icameraeffectivedata/)\> [get_Camera](./get_camera/)() | कैमरा की सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [ICameraEffectiveData](../icameraeffectivedata/)। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ContourColor](./get_contourcolor/)() | कंटूर का रंग लौटाता है। केवल-पढ़ने योग्य [System::Drawing::Color](../../system.drawing/color/)। |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | 3D कंटूर की चौड़ाई लौटाता है। केवल-पढ़ने योग्य **double**। |
| virtual **double** [get_Depth](./get_depth/)() | 3D आकार की गहराई लौटाता है। केवल-पढ़ने योग्य **double**। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ExtrusionColor](./get_extrusioncolor/)() | एक्सट्रूज़न का रंग लौटाता है। केवल-पढ़ने योग्य [System::Drawing::Color](../../system.drawing/color/)। |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। केवल-पढ़ने योग्य **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRigEffectiveData](../ilightrigeffectivedata/)\> [get_LightRig](./get_lightrig/)() | लाइट का प्रकार लौटाता है। केवल-पढ़ने योग्य [ILightRigEffectiveData](../ilightrigeffectivedata/)। |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | मैटरियल का प्रकार लौटाता है। केवल-पढ़ने योग्य [MaterialPresetType](../materialpresettype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम वस्तुओं का हैश बनाना सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स को क्लोन करना सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ का कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ का कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को कम करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nथ टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणी

इस इंटरफ़ेस का उपयोग [IThreeDFormat](../ithreedformat/) इंटरफ़ेस के साथ मिलकर प्रभावी फ़ॉर्मेटिंग मानों को लौटाने के लिए किया जाता है, जिसमें विरासत लागू होती है।

## देखें

* क्लास [IThreeDParamSource](../ithreedparamsource/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)