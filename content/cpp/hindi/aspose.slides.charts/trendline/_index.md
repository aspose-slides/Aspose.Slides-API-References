---
title: Trendline
second_title: Aspose.Slides for C++ API संदर्भ
description: क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है
type: docs
weight: 1366
url: /hi/aspose.slides.charts/trendline/
---
## Trendline क्लास

क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | परामीटर "text" में दिए गए पाठ के साथ TextFrameForOverriding को प्रारंभ करें। यदि TextFrameForOverriding पहले से ही प्रारंभ किया गया है तो केवल उसका पाठ बदलें। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **double** [get_Backward](./get_backward/)() override | ट्रेंड लाइन द्वारा श्रृंखला के डेटा से पहले विस्तारित होने वाले वर्गों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें **double**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | निर्दिष्ट करता है कि ट्रेंडलाइन के समीकरण को चार्ट पर प्रदर्शित किया गया है (Rsquaredvalue के समान लेबल में)। पढ़ें **bool**। |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | निर्दिष्ट करता है कि ट्रेंडलाइन का R-squared मान चार्ट पर प्रदर्शित किया गया है (समीकरण के समान लेबल में)। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | ट्रेंड लाइन के स्वरूप का प्रतिनिधित्व करता है। पढ़ें [IFormat](../iformat/)। |
| **double** [get_Forward](./get_forward/)() override | ट्रेंड लाइन द्वारा श्रृंखला के डेटा के बाद विस्तारित होने वाले वर्गों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें **double**। |
| **double** [get_Intercept](./get_intercept/)() override | ट्रेंडलाइन जहाँ y-अक्ष को काटेगा, उस मान को निर्धारित करता है। यह प्रॉपर्टी केवल तब समर्थित होगी जब ट्रेंडलाइन प्रकार exp, linear, या poly हो। पढ़ें **double**। |
| **uint8_t** [get_Order](./get_order/)() override | बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 और 6 के बीच होना चाहिए। पढ़ें **uint8_t**। |
| **uint8_t** [get_Period](./get_period/)() override | ट्रेंडलाइन के लिए मूविंग एवरेज का अवधि निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 और 255 के बीच होना चाहिए। पढ़ें **uint8_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | इस ट्रेंडलाइन से संबंधित लेजेंड प्रविष्टि का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [ILegendEntryProperties](../ilegendentryproperties/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | समृद्ध स्वरूपित टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह स्वरूपित टेक्स्ट मान डेटा लेबल के ऑटो-जनरेटेड टेक्स्ट को अधिलेखित करता है। डेटा लेबल का ऑटो-जनरेटेड टेक्स्ट वह टेक्स्ट है जिसे ShowSeriesName, ShowValue, ... प्रॉपर्टीज़ द्वारा प्रबंधित किया जाता है और TextFormatManager.TextFormat प्रॉपर्टी के साथ स्वरूपित किया जाता है। केवल-पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/)। |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | ट्रेंडलाइन का नाम प्राप्त करता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | ट्रेंड लाइन का प्रकार प्राप्त करता है। पढ़ें [Charts::TrendlineType](../trendlinetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी कन्स्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी कन्स्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू प्रकार के ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Backward](./set_backward/)(**double**) override | ट्रेंड लाइन द्वारा श्रृंखला के डेटा से पहले विस्तारित होने वाले वर्गों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। लिखें **double**। |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | ट्रेंडलाइन के समीकरण को चार्ट पर प्रदर्शित किया जाना निर्दिष्ट करता है (Rsquaredvalue के समान लेबल में)। लिखें **bool**। |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | ट्रेंडलाइन का R-squared मान चार्ट पर प्रदर्शित किया जाना निर्दिष्ट करता है (समीकरण के समान लेबल में)। लिखें **bool**। |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | ट्रेंड लाइन के स्वरूप का प्रतिनिधित्व करता है। लिखें [IFormat](../iformat/)। |
| void [set_Forward](./set_forward/)(**double**) override | ट्रेंडलाइन द्वारा श्रृंखला के डेटा के बाद विस्तारित होने वाले वर्गों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। लिखें **double**। |
| void [set_Intercept](./set_intercept/)(**double**) override | ट्रेंडलाइन जहाँ y-अक्ष को काटेगा, उस मान को निर्धारित करता है। यह प्रॉपर्टी केवल तब समर्थित होगी जब ट्रेंडलाइन प्रकार exp, linear, या poly हो। लिखें **double**। |
| void [set_Order](./set_order/)(**uint8_t**) override | बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 और 6 के बीच होना चाहिए। लिखें **uint8_t**। |
| void [set_Period](./set_period/)(**uint8_t**) override | ट्रेंडलाइन के लिए मूविंग एवरेज की अवधि निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 और 255 के बीच होना चाहिए। लिखें **uint8_t**। |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | ट्रेंडलाइन का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | ट्रेंड लाइन का प्रकार सेट करता है। लिखें [Charts::TrendlineType](../trendlinetype/)। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'th टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [ITrendline](../itrendline/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)