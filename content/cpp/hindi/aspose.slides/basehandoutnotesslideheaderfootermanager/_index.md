---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्लेसहोल्डर्स के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है, जिसमें सभी प्रकार के हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।
type: docs
weight: 118
url: /hi/aspose.slides/basehandoutnotesslideheaderfootermanager/
---
## BaseHandoutNotesSlideHeaderFooterManager क्लास

Represents manager which holds behavior of the placeholders, including header placeholder for all types handout and notes slides.

```cpp
class BaseHandoutNotesSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                                 public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | यह बताने वाला मान प्राप्त करता है कि तिथि-समय प्लेसहोल्डर मौजूद है। पढ़ें**bool**। |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | यह बताने वाला मान प्राप्त करता है कि फ़ूटर प्लेसहोल्डर मौजूद है। पढ़ें **bool**। |
| **bool** [get_IsHeaderVisible](./get_isheadervisible/)() override | यह बताने वाला मान प्राप्त करता है कि हेडर प्लेसहोल्डर मौजूद है। पढ़ें **bool**। |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | यह बताने वाला मान प्राप्त करता है कि पेज नंबर प्लेसहोल्डर मौजूद है। पढ़ें**bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। कोई चीज़ कॉपी नहीं करता, वास्तव में केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कोई चीज़ कॉपी नहीं करता, वास्तव में केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-कम्पेयर करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | स्लाइड तिथि-समय प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | स्लाइड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | स्लाइड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | स्लाइड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। |
| void [SetHeaderText](./setheadertext/)([System::String](../../system/string/)) override | स्लाइड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| void [SetHeaderVisibility](./setheadervisibility/)(**bool**) override | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (शेअर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंट का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* क्लास [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)