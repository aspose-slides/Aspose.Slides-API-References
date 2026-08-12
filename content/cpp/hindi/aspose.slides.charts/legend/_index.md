---
title: Legend
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट की लेजेंड गुणों को दर्शाता है।
type: docs
weight: 1262
url: /hi/aspose.slides.charts/legend/
---
## Legend क्लास

चार्ट की लेजेंड गुणों का प्रतिनिधित्व करता है।

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **float** [get_ActualHeight](./get_actualheight/)() override | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड कॉल करें। **float** पढ़ें। |
| **float** [get_ActualWidth](./get_actualwidth/)() override | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड कॉल करें। **float** पढ़ें। |
| **float** [get_ActualX](./get_actualx/)() override | चार्ट तत्व की वास्तविक x स्थिति (बाएँ) को चार्ट के बाएँ ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड कॉल करें। **float** पढ़ें। |
| **float** [get_ActualY](./get_actualy/)() override | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड कॉल करें। **float** पढ़ें। |
| **float** [get_Bottom](./get_bottom/)() override | निचला। केवल-पढ़ने योग्य **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | लेजेंड प्रविष्टियों को प्राप्त करता है। केवल-पढ़ने योग्य [ILegendEntryCollection](../ilegendentrycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर चार्ट में डेटा पॉइंट के संबंधित लेजेंड प्रविष्टि के गुण प्राप्त करता है। चार्ट प्रकारों के मामले में: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, डेटा पॉइंट पहली श्रृंखला से लिया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | लेजेंड का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../iformat/)। |
| **float** [get_Height](./get_height/)() override | लेजेंड की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में लौटाता है। **float** पढ़ें। |
| **bool** [get_Overlay](./get_overlay/)() override | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति है या नहीं। **bool** पढ़ें। |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। X, Y, Width, Height प्रॉपर्टीज़ के गैर-NaN मान इस प्रॉपर्टी के प्रभाव को ओवरराइड करते हैं। [LegendPositionType](../legendpositiontype/) पढ़ें। |
| **float** [get_Right](./get_right/)() override | दायाँ। केवल-पढ़ने योग्य **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | टेक्स्ट फ़ॉर्मेट। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| **float** [get_Width](./get_width/)() override | लेजेंड की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में लौटाता है। **float** पढ़ें। |
| **float** [get_X](./get_x/)() override | लेजेंड का x निर्देशांक को चार्ट की चौड़ाई के अंश के रूप में लौटाता है। **float** पढ़ें। |
| **float** [get_Y](./get_y/)() override | लेजेंड का y निर्देशांक को चार्ट की ऊँचाई के अंश के रूप में लौटाता है। **float** पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का analogue. कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का analogue। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट लक्ष्यटाइप द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का analogue। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का analogue. कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [set_Height](./set_height/)(**float**) override | लेजेंड की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में सेट करता है। **float** लिखें। |
| void [set_Overlay](./set_overlay/)(**bool**) override | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति है या नहीं। **bool** लिखें। |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। X, Y, Width, Height प्रॉपर्टीज़ के गैर-NaN मान इस प्रॉपर्टी के प्रभाव को ओवरराइड करते हैं। [LegendPositionType](../legendpositiontype/) लिखें। |
| void [set_Width](./set_width/)(**float**) override | लेजेंड की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में सेट करता है। **float** लिखें। |
| void [set_X](./set_x/)(**float**) override | लेजेंड के x निर्देशांक को चार्ट की चौड़ाई के अंश के रूप में सेट करता है। **float** लिखें। |
| void [set_Y](./set_y/)(**float**) override | लेजेंड के y निर्देशांक को चार्ट की ऊँचाई के अंश के रूप में सेट करता है। **float** लिखें। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | nवें टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का analogue. कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [ILegend](../ilegend/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)