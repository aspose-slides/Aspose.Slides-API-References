---
title: IAutoShapeLock
second_title: Aspose.Slides for C++ API संदर्भ
description: पैरेंट AutoshapeEx पर कौन-से ऑपरेशन्स निष्क्रिय हैं, यह निर्धारित करता है।
type: docs
weight: 1379
url: /hi/aspose.slides/iautoshapelock/
---
## IAutoShapeLock वर्ग

Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | निश्चित करता है कि एडजस्ट मानों में परिवर्तन प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | निश्चित करता है कि एरोहेड्स में परिवर्तन प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | निर्धारित करता है कि आकार को आकार बदलते समय अनुपात बनाए रखना आवश्यक है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | निर्धारित करता है कि इस आकार की कंटूर में प्रत्यक्ष परिवर्तन प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | यदि सभी लॉक-फ़्लैग अक्षम हों तो true लौटाता है। केवल-पढ़ने योग्य **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | निर्धारित करता है कि इस आकार को स्थानांतरित करना प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | निर्धारित करता है कि इस आकार का रोटेशन एंगल बदलना प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | निर्धारित करता है कि इस आकार का चयन करना प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | निर्धारित करता है कि आकार के प्रकार में परिवर्तन प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | निर्धारित करता है कि इस आकार को आकार बदलना प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | निर्धारित करता है कि टेक्स्ट का संपादन प्रतिबंधित है या नहीं। **bool** पढ़ता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | निश्चित करता है कि एडजस्ट मानों में परिवर्तन प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | निश्चित करता है कि एरोहेड्स में परिवर्तन प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | निर्धारित करता है कि आकार को आकार बदलते समय अनुपात बनाए रखना आवश्यक है या नहीं। **bool** लिखता है। |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | निर्धारित करता है कि इस आकार की कंटूर में प्रत्यक्ष परिवर्तन प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | निर्धारित करता है कि इस आकार को स्थानांतरित करना प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | निर्धारित करता है कि इस आकार का रोटेशन एंगल बदलना प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | निर्धारित करता है कि इस आकार का चयन करना प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | निर्धारित करता है कि आकार के प्रकार में परिवर्तन प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | निर्धारित करता है कि इस आकार को आकार बदलना प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | निर्धारित करता है कि टेक्स्ट का संपादन प्रतिबंधित है या नहीं। **bool** लिखता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयरिंग के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कनवर्ट करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [IBaseShapeLock](../ibaseshapelock/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)