---
title: IConnectorLock
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि पैरेंट कनेक्टर पर कौन-से ऑपरेशन अक्षम हैं।
type: docs
weight: 1860
url: /hi/aspose.slides/iconnectorlock/
---
## IConnectorLock क्लास

निर्धारित करता है कि कौन-से ऑपरेशन पैरेंट [Connector](../connector/) पर अक्षम हैं।

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है, जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है, जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | निर्धारित करता है कि परिवर्तन समायोजित मानों को प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | निर्धारित करता है कि एरोहेड्स के परिवर्तन को प्रतिबंधित किया गया है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | निर्धारित करता है कि आकार को रिसाइज़ करने पर पहलू अनुपात बनाए रखना आवश्यक है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | निर्धारित करता है कि इस आकार के कंटूर को सीधे बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | यदि सभी लॉक-फ्लैग अक्षम हैं तो true लौटाता है। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | निर्धारित करता है कि इस आकार को ले जाना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | निर्धारित करता है कि इस आकार के घूर्णन कोण को बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | निर्धारित करता है कि इस आकार को चुनना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | निर्धारित करता है कि आकार प्रकार को बदलना प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | निर्धारित करता है कि इस आकार का रिसाइज़ प्रतिबंधित है या नहीं। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | निर्धारित करता है कि परिवर्तन समायोजित मानों को प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | निर्धारित करता है कि एरोहेड्स के परिवर्तन को प्रतिबंधित किया गया है या नहीं। लिखें **bool**। |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | निर्धारित करता है कि आकार रिसाइज़ पर पहलू अनुपात बनाए रखना आवश्यक है या नहीं। लिखें **bool**। |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | निर्धारित करता है कि इस आकार के कंटूर को सीधे बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | निर्धारित करता है कि इस आकार को ले जाना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | निर्धारित करता है कि इस आकार के घूर्णन कोण को बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | निर्धारित करता है कि इस आकार को चुनना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | निर्धारित करता है कि आकार प्रकार को बदलना प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | निर्धारित करता है कि इस आकार का रिसाइज़ प्रतिबंधित है या नहीं। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IBaseShapeLock](../ibaseshapelock/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)