---
title: ILegend
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: चार्ट की लेजेंड गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 1080
url: /hi/aspose.slides.charts/ilegend/
---
## ILegend क्लास

चार्ट की लेजेंड गुणों का प्रतिनिधित्व करता है।

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुसरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुसरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | चार्ट तत्व का वास्तविक x स्थान (बाएँ) चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अंश के रूप में प्राप्त करता है। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट को लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | लेजेंड प्रविष्टियों को प्राप्त करता है। केवल-पढ़ने योग्य [ILegendEntryCollection](../ilegendentrycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | निर्दिष्ट इंडेक्स पर चार्ट में डेटा बिंदु के अनुरूप लेजेंड प्रविष्टि की गुणधर्म प्राप्त करता है। चार्ट प्रकारों के मामलों में: बार-ऑफ़-पाई, एक्सप्लोडेड पाई, एक्सप्लोडेड पाई 3D, पाई, पाई 3D, पाई-ऑफ़-पाई, डेटा बिंदु पहली सीरीज से लिया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | लेजेंड का फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../iformat/)। |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में निर्दिष्ट करता है। **float** पढ़ें। |
| virtual **bool** [get_Overlay](./get_overlay/)() | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति है या नहीं। **bool** पढ़ें। |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | चार्ट पर लेजेंड की स्थिति को निर्दिष्ट करता है। X, Y, Width, Heigt गुणों के गैर-NaN मान इस प्रॉपर्टी के प्रभाव को ओवरराइड करते हैं। [LegendPositionType](../legendpositiontype/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | चार्ट तत्व के दाएँ किनारे को चार्ट की चौड़ाई के अंश के रूप में प्राप्त करता है। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में निर्दिष्ट करता है। **float** पढ़ें। |
| virtual **float** [get_X](../ilayoutable/get_x/)() | चार्ट तत्व का x स्थान (बाएँ) को चार्ट की चौड़ाई के अंश के रूप में निर्दिष्ट करता है। **float** पढ़ें। |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अंश के रूप में निर्दिष्ट करता है। **float** पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के अंश के रूप में निर्दिष्ट करता है। **float** लिखें। |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति है या नहीं। **bool** लिखें। |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | चार्ट पर लेजेंड की स्थिति को निर्दिष्ट करता है। X, Y, Width, Heigt गुणों के गैर-NaN मान इस प्रॉपर्टी के प्रभाव को ओवरराइड करते हैं। [LegendPositionType](../legendpositiontype/) लिखें। |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के अंश के रूप में निर्दिष्ट करता है। **float** लिखें। |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | चार्ट तत्व का x स्थान (बाएँ) को चार्ट की चौड़ाई के अंश के रूप में निर्दिष्ट करता है। **float** लिखें। |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अंश में निर्दिष्ट करता है। **float** लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को शेरड के बजाय एक weak पॉइंटर सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [ILayoutable](../ilayoutable/)
* क्लास [IFormattedTextContainer](../iformattedtextcontainer/)
* क्लास [IActualLayout](../iactuallayout/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)