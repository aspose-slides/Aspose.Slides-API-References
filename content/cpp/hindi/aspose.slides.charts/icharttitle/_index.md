---
title: IChartTitle
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 911
url: /hi/aspose.slides.charts/icharttitle/
---
## IChartTitle क्लास

चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | परामीटर \"text\" में दिए गए पाठ के साथ TextFrameForOverriding को आरंभ करता है। यदि TextFrameForOverriding पहले से ही आरंभ किया गया है तो केवल उसका पाठ बदलता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके करती है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | चार्ट तत्व की वास्तविक x स्थिति (बाएँ) को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अनुपात में प्राप्त करता है। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | शीर्षक के fill, line, effect शैलियों को लौटाता है। केवल-पढ़ने योग्य [IFormat](../iformat/)। |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के अनुपात में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **bool** [get_Overlay](./get_overlay/)() | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति हो। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | चार्ट तत्व के दाएँ को चार्ट की चौड़ाई के अनुपात में प्राप्त करता है। केवल-पढ़ने योग्य **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | रिच फ़ॉर्मेटेड टेक्स्ट शामिल कर सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट वैल्यू ऑटो-जनरेटेड टेक्स्ट को ओवरराइड करती है। ऑटो-जनरेटेड टेक्स्ट डेटा लेबल, वैल्यू एक्सिस के डिस्प्ले यूनिट लेबल, एक्सिस टाइटल, चार्ट टाइटल, ट्रेंडलाइन लेबल की एक अप्रत्यक्ष प्रॉपर्टी है। ऑटो-जनरेटेड टेक्स्ट [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) प्रॉपर्टी के साथ फ़ॉर्मेटेड है। केवल-पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/)। |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के अनुपात में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ilayoutable/get_x/)() | चार्ट तत्व की x स्थिति (बाएँ) को चार्ट की चौड़ाई के अनुपात में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अनुपात में निर्दिष्ट करता है। पढ़ें **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इन्स्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइजेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | चार्ट तत्व की ऊँचाई को चार्ट की ऊँचाई के अनुपात में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति हो। लिखें **bool**। |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | चार्ट तत्व की चौड़ाई को चार्ट की चौड़ाई के अनुपात में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | चार्ट तत्व की x स्थिति (बाएँ) को चार्ट की चौड़ाई के अनुपात में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | चार्ट तत्व के शीर्ष को चार्ट की ऊँचाई के अनुपात में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; उसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; उसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; उसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; उसके बजाय स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [ILayoutable](../ilayoutable/)
* क्लास [IOverridableText](../ioverridabletext/)
* क्लास [IActualLayout](../iactuallayout/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)