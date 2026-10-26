---
title: IChartDataWorkbook
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एम्बेडेड Excel वर्कबुक तक पहुंच प्रदान करता है
type: docs
weight: 729
url: /hi/aspose.slides.charts/ichartdataworkbook/
---
## IChartDataWorkbook क्लास


एम्बेडेड [Excel](../../aspose.slides.excel/) वर्कबुक तक पहुंच प्रदान करता है

```cpp
class IChartDataWorkbook : public virtual System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual void [CalculateFormulas](./calculateformulas/)() | वर्कबुक में सभी सूत्रों की गणना करता है और संबंधित सेल मानों को अपडेट करता है. |
| virtual void [Clear](./clear/)(**int32_t**) | शीट पर सभी सेल मानों को साफ़ करता है |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग कर ऑब्जेक्ट्स की तुलना करता है. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN भी नहीं. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_Worksheet](./get_worksheet/)(**int32_t**) | निर्दिष्ट अनुक्रमांक पर इस वर्कबुक का वर्कशीट लौटाता है. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheetCollection](../ichartdataworksheetcollection/)\> [get_Worksheets](./get_worksheets/)() | वर्कशीट्स का एक संग्रह प्राप्त करता है. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), **int32_t**, **int32_t**) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [GetCell](./getcell/)(**int32_t**, **int32_t**, **int32_t**) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [GetCell](./getcell/)(**int32_t**, [System::String](../../system/string/)) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [GetCell](./getcell/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [GetCell](./getcell/)(**int32_t**, **int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | चार्ट सीरीज़ या श्रेणियों के लिए उपयोग किया जा सकने वाला सेल प्राप्त करता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\> [GetCellCollection](./getcellcollection/)([System::String](../../system/string/), **bool**) | सेल सेट प्राप्त करता है. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर. कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है. C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं. C# 'is' ऑपरेटर का समानांतर. |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग लागू करता है. सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर. कस्टम टाइप्स की क्लोनिंग सक्षम करता है. |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है. सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर. वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर. वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर सेट करता है (साझा के बजाय). कंटेनर्स में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है. |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है. सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है. सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर. कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने की अनुमति देता है. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है. |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अन्लॉकिंग लागू करता है. सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है. सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है. सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें. |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है. सभी आंतरिक डेटा संरचनाओं को मुक्त करता है. |
## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)