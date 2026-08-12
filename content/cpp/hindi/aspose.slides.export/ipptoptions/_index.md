---
title: IPptOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: ऐसे विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रेजेंटेशन को PPT फॉर्मेट में कैसे सहेजा जाता है।
type: docs
weight: 287
url: /hi/aspose.slides.export/ipptoptions/
---
## IPptOptions क्लास

प्रेजेंटेशन को PPT फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```cpp
class IPptOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थ का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान (जिसमें NaN भी शामिल है) के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान (जिसमें NaN भी शामिल है) के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की दृश्य शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रति प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट को दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| virtual [System::Guid](../../system/guid/) [get_RootDirectoryClsid](./get_rootdirectoryclsid/)() | रूट डायरेक्टरी प्रविष्टि में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है। इसे दस्तावेज़ के अनुप्रयोग के COM सक्रियण के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मूल्य '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से संबन्धित है। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंनरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों का कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों का कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ मान प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशिष्ट रूप। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशिष्ट रूप। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की दृश्य शैली को सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रति प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट को दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| virtual void [set_RootDirectoryClsid](./set_rootdirectoryclsid/)([System::Guid](../../system/guid/)) | रूट डायरेक्टरी प्रविष्टि में संग्रहीत ऑब्जेक्ट क्लास GUID (CLSID) को दर्शाता है। इसे दस्तावेज़ के अनुप्रयोग के COM सक्रियण के लिए उपयोग किया जा सकता है। डिफ़ॉल्ट मूल्य '64818D11-4F9B-11CF-86EA-00AA00B929E8' है जो 'Microsoft Powerpoint.Slide.8' से संबन्धित है। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंनरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [ISaveOptions](../isaveoptions/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)