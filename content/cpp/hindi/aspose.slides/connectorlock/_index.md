---
title: ConnectorLock
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि पैरेंट कनेक्टर पर कौन-से ऑपरेशन्स अक्षम हैं।
type: docs
weight: 495
url: /hi/aspose.slides/connectorlock/
---
## ConnectorLock क्लास

Determines which operations are disabled on the parent [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | निर्धारित करता है कि समायोजन मानों में परिवर्तन निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | निर्धारित करता है कि एरोहेड्स में परिवर्तन निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | निर्धारित करता है कि आकार को आकार बदलने पर अनुपात बनाए रखना चाहिए या नहीं। पढ़ें **bool**। |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | निर्धारित करता है कि इस आकार की रूपरेखा में प्रत्यक्ष परिवर्तन निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | निर्धारित करता है कि इस आकार को समूह में जोड़ना निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | यदि सभी लॉक-फ़्लैग निष्क्रिय हैं तो true लौटाता है। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_PositionMove](./get_positionmove/)() override | निर्धारित करता है कि इस आकार को स्थानांतरित करना निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | निर्धारित करता है कि इस आकार के घूर्णन कोण में परिवर्तन निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | निर्धारित करता है कि इस आकार का चयन करना निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | निर्धारित करता है कि आकार के प्रकार में परिवर्तन निषेध है या नहीं। पढ़ें **bool**। |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | निर्धारित करता है कि इस आकार का आकार बदलना निषेध है या नहीं। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | निर्धारित करता है कि समायोजन मानों में परिवर्तन निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | निर्धारित करता है कि एरोहेड्स में परिवर्तन निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | निर्धारित करता है कि आकार को आकार बदलने पर अनुपात बनाए रखना चाहिए या नौ नहीं। लिखें **bool**। |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | निर्धारित करता है कि इस आकार की रूपरेखा में प्रत्यक्ष परिवर्तन निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | निर्धारित करता है कि इस आकार को समूह में जोड़ना निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | निर्धारित करता है कि इस आकार को स्थानांतरित करना निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | निर्धारित करता है कि इस आकार के घूर्णन कोण में परिवर्तन निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | निर्धारित करता है कि इस आकार का चयन करना निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | निर्धारित करता है कि आकार के प्रकार में परिवर्तन निषेध है या नौ नहीं। लिखें **bool**। |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | निर्धारित करता है कि इस आकार का आकार बदलना निषेध है या नौ नहीं। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए हुए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए हुए रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए हुए रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [BaseShapeLock](../baseshapelock/)
* क्लास [IConnectorLock](../iconnectorlock/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)