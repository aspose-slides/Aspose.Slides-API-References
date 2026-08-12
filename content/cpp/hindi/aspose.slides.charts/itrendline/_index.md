---
title: ITrendline
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है
type: docs
weight: 1223
url: /hi/aspose.slides.charts/itrendline/
---
## ITrendline क्लास

Class represents trend line of chart series

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | पैरामीटर \"text\" में टेक्स्ट के साथ TextFrameForOverriding को प्रारंभ करता है। यदि TextFrameForOverriding पहले से ही प्रारंभ हो चुका है तो केवल उसका टेक्स्ट बदल देता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के साथ भी, बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के साथ भी, बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **double** [get_Backward](./get_backward/)() | ट्रेंड लाइन उस श्रृंखला के डेटा से पहले कितनी श्रेणियों (या स्कैटर चार्ट पर इकाइयों) तक विस्तारित होती है, यह निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट्स में मान कोई भी अपर नकारात्मक मान हो सकता है। पढ़ें **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर दिखाया जाए (Rsquaredvalue के समान लेबल में)। पढ़ें **bool**। |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | निर्दिष्ट करता है कि ट्रेंडलाइन का R-squared मान चार्ट पर दिखाया जाए (समीकरण के समान लेबल में)। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | ट्रेंड लाइन का प्रारूप दर्शाता है। पढ़ें [IFormat](../iformat/)। |
| virtual **double** [get_Forward](./get_forward/)() | ट्रेंडलाइन उन श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो डेटा के बाद विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट्स में मान कोई भी अपर-नकारात्मक मान हो सकता है। पढ़ें **double**। |
| virtual **double** [get_Intercept](./get_intercept/)() | ट्रेंडलाइन जहाँ y-अक्ष को काटेगी, उस मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल उन प्रकारों के लिए समर्थित है जिनका प्रकार exp, linear या poly है। पढ़ें **double**। |
| virtual **uint8_t** [get_Order](./get_order/)() | बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। अन्य ट्रेंड लाइन प्रकारों के लिए इसे अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। पढ़ें **uint8_t**। |
| virtual **uint8_t** [get_Period](./get_period/)() | मूविंग एवरेज ट्रेंड लाइन के लिए अवधि निर्दिष्ट करता है। अन्य ट्रेंड लाइन वैरिएंट्स के लिए इसे अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। पढ़ें **uint8_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | इस ट्रेंडलाइन से संबंधित लेजेंड प्रविष्टि दर्शाता है। केवल-पढ़ने योग्य [ILegendEntryProperties](../ilegendentryproperties/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | समृद्ध स्वरूपित टेक्स्ट समाहित कर सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह स्वरूपित टेक्स्ट मान ऑटो-जनरेटेड टेक्स्ट को ओवरराइड करता है। ऑटो-जनरेटेड टेक्स्ट डेटा लेबल, वैल्यू एक्सिस की डिस्प्ले यूनिट लेबल, एक्सिस टाइटल, चार्ट टाइटल, और ट्रेंडलाइन लेबल की एक अप्रत्यक्ष प्रॉपर्टी है। ऑटो-जनरेटेड टेक्स्ट [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) प्रॉपर्टी के साथ स्वरूपित किया गया है। केवल-पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/)। |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | ट्रेंडलाइन का नाम प्राप्त करता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | ट्रेंड लाइन का प्रकार प्राप्त करता है। पढ़ें [TrendlineType](../trendlinetype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टैंस है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Backward](./set_backward/)(**double**) | ट्रेंड लाइन उन श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो डेटा से पहले विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट्स में मान कोई भी अपर नकारात्मक मान हो सकता है। लिखें **double**। |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | निर्धारित करता है कि ट्रेंडलाइन का समीकरण चार्ट पर दिखाया जाए (Rsquaredvalue के समान लेबल में)। लिखें **bool**। |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | निर्धारित करता है कि ट्रेंडलाइन का R-squared मान चार्ट पर दिखाया जाए (समीकरण के समान लेबल में)। लिखें **bool**। |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | ट्रेंड लाइन का फ़ॉर्मेट दर्शाता है। लिखें [IFormat](../iformat/)। |
| virtual void [set_Forward](./set_forward/)(**double**) | ट्रेंडलाइन उन श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो डेटा के बाद विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट्स में मान कोई भी अपर-नकारात्मक मान हो सकता है। लिखें **double**। |
| virtual void [set_Intercept](./set_intercept/)(**double**) | ट्रेंडलाइन जहाँ y-अक्ष को काटेगी, उस मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल उन प्रकारों के लिए समर्थित है जिनका प्रकार exp, linear या poly है। लिखें **double**। |
| virtual void [set_Order](./set_order/)(**uint8_t**) | बहुपद ट्रेंड लाइन का क्रम निर्धारित करता है। अन्य प्रकारों के लिए इसे अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। लिखें **uint8_t**। |
| virtual void [set_Period](./set_period/)(**uint8_t**) | मूविंग एवरेज ट्रेंड लाइन के लिए अवधि निर्धारित करता है। अन्य वैरिएंट्स के लिए इसे अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। लिखें **uint8_t**। |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | ट्रेंडलाइन का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | ट्रेंड लाइन का प्रकार सेट करता है। लिखें [TrendlineType](../trendlinetype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [IOverridableText](../ioverridabletext/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)