---
title: AutoShapeLock
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि पैरेंट AutoshapeEx पर कौन सी क्रियाएँ अक्षम हैं।
type: docs
weight: 79
url: /hi/aspose.slides/autoshapelock/
---
## AutoShapeLock क्लास


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी वैल्यू के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी वैल्यू के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | समायोजन मानों में परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | तीर-सिरों में परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | आकार को आकार बदलते समय अनुपात बनाए रखने के लिए बाध्य है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | इस आकार की रूपरेखा में प्रत्यक्ष परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | इस आकार को समूह में जोड़ना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | यदि सभी लॉक-फ़्लैग निष्क्रिय हों तो true लौटाता है। केवल-पठन **bool**। |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | इस आकार को ले जाना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | इस आकार का घूर्णन कोण बदलना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | इस आकार का चयन करना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | आकार के प्रकार को बदलना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | इस आकार का आकार बदलना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_TextLocked](./get_textlocked/)() override | पाठ को संपादित करना निषिद्ध है या नहीं निर्धारित करता है। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांक। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांक। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टांस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांक। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांक। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | समायोजन मानों में परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | तीर-सिरों में परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | आकार को आकार बदलते समय अनुपात बनाए रखने के लिए बाध्य है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | इस आकार की रूपरेखा में प्रत्यक्ष परिवर्तन निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | इस आकार को समूह में जोड़ना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | इस आकार को ले जाना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | इस आकार का घूर्णन कोण बदलना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | इस आकार का चयन करना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | आकार के प्रकार को बदलना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | इस आकार का आकार बदलना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | पाठ को संपादित करना निषिद्ध है या नहीं निर्धारित करता है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटरों को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांक। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## संबंधित देखें

* क्लास [BaseShapeLock](../baseshapelock/)
* क्लास [IAutoShapeLock](../iautoshapelock/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)