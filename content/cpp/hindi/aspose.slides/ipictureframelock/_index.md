---
title: IPictureFrameLock
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि पैरेंट PictureFrameEx पर कौन-से ऑपरेशन निष्क्रिय हैं।
type: docs
weight: 3264
url: /hi/aspose.slides/ipictureframelock/
---
## IPictureFrameLock क्लास


निर्धारित करता है कि कौन-से ऑपरेशन अभिभावक PictureFrameEx पर निष्क्रिय हैं।

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | निर्धारित करता है कि समायोजन मानों (adjust values) को बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | निर्धारित करता है कि तीर सिरों (arrowheads) को बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | निर्धारित करता है कि आकार को आकार बदलते समय अनुपात (aspect ratio) संरक्षित रखना आवश्यक है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | निर्धारित करता है कि छवि क्रॉपिंग प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | निर्धारित करता है कि इस आकार की रूपरेखा (contour) को सीधे बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | यदि सभी लॉक-फ़्लैग निष्क्रिय हैं तो true लौटाता है। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | निर्धारित करता है कि इस आकार को ले जाना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | निर्धारित करता है कि इस आकार का घूर्णन कोण बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | निर्धारित करता है कि इस आकार का चयन करना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | निर्धारित करता है कि आकार प्रकार को बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | निर्धारित करता है कि इस आकार का आकार बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बल्कि नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बल्कि नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट का nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के मामलों के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | निर्धारित करता है कि समायोजन मानों को बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | निर्धारित करता है कि arrowheads को बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | निर्धारित करता है कि आकार को आकार बदलते समय अनुपात संरक्षित रखना आवश्यक है या नहीं। लिखें **bool**। |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | निर्धारित करता है कि छवि क्रॉपिंग प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | निर्धारित करता है कि इस आकार की रूपरेखा को सीधे बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | निर्धारित करता है कि इस आकार को ले जाना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | निर्धारित करता है कि इस आकार का घूर्णन कोण बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | निर्धारित करता है कि इस आकार का चयन करना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | निर्धारित करता है कि आकार प्रकार को बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | निर्धारित करता है कि इस आकार का आकार बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को साझा के बजाय कमजोर पॉइंटर सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वेक रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वेक रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IBaseShapeLock](../ibaseshapelock/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)