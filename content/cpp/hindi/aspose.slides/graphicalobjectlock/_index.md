---
title: GraphicalObjectLock
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि पैरेंट GraphicalObject पर कौन सी क्रियाएँ निष्क्रिय हैं।
type: docs
weight: 1184
url: /hi/aspose.slides/graphicalobjectlock/
---
## GraphicalObjectLock क्लास

पैरेंट [GraphicalObject](../graphicalobject/) पर कौन सी ऑपरेशन्स निष्क्रिय हैं, यह निर्धारित करता है।

```cpp
class GraphicalObjectLock : public Aspose::Slides::BaseShapeLock,
                            public Aspose::Slides::IGraphicalObjectLock
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैन्टिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | री-साइज़िंग पर आकार अनुपात को बनाए रखने के लिए शैप निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_DrilldownLocked](./get_drilldownlocked/)() override | इस ऑब्जेक्ट के सबशेप्स के चयन को प्रतिबंधित करने का निर्धारण करता है। पढ़ें **bool**। |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | इस शैप को समूह में जोड़ने को प्रतिबंधित करने का निर्धारण करता है। पढ़ें **bool**। |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | यदि सभी लॉक-फ़्लैग निष्क्रिय हैं तो true लौटाता है। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | इस शैप को स्थानांतरित करने को प्रतिबंधित करने का निर्धारण करता है। पढ़ें **bool**। |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | इस शैप को चुनने को प्रतिबंधित करने का निर्धारण करता है। पढ़ें **bool**। |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | इस शैप के आकार बदलने को प्रतिबंधित करने का निर्धारण करता है। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | री-साइज़िंग पर आकार अनुपात को बनाए रखने के लिए शैप निर्धारित करता है। लिखें **bool**। |
| void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) override | इस ऑब्जेक्ट के सबशेप्स के चयन को प्रतिबंधित करने का निर्धारण करता है। लिखें **bool**। |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | इस शैप को समूह में जोड़ने को प्रतिबंधित करने का निर्धारण करता है। लिखें **bool**। |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | इस शैप को स्थानांतरित करने को प्रतिबंधित करने का निर्धारण करता है। लिखें **bool**। |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | इस शैप को चुनने को प्रतिबंधित करने का निर्धारण करता है। लिखें **bool**। |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | इस शैप के आकार बदलने को प्रतिबंधित करने का निर्धारण करता है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर नहीं) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [BaseShapeLock](../baseshapelock/)
* क्लास [IGraphicalObjectLock](../igraphicalobjectlock/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)