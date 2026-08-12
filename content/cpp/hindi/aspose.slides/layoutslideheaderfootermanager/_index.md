---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API संदर्भ
description: लेआउट स्लाइड फुटर, तिथि-समय, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।
type: docs
weight: 4317
url: /hi/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager वर्ग

लेआउट स्लाइड फुटर, तिथि-समय, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक का प्रतिनिधित्व करता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | तिथि-समय प्लेसहोल्डर के मौजूद होने का संकेत देने वाला मान प्राप्त करता है। Read**bool**। |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | फुटर प्लेसहोल्डर के मौजूद होने का संकेत देने वाला मान प्राप्त करता है। Read **bool**। |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | पेज नंबर प्लेसहोल्डर के मौजूद होने का संकेत देने वाला मान प्राप्त करता है। Read**bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर पर टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होते हैं। |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होते हैं। |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | स्लाइड तिथि-समय प्लेसहोल्डर पर टेक्स्ट सेट करता है। |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | स्लाइड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | लेआउट स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर पर टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होते हैं। |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | लेआउट स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर होते हैं। |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | स्लाइड फुटर प्लेसहोल्डर पर टेक्स्ट सेट करता है। |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | स्लाइड फुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | लेआउट स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का मतलब है कि प्लेसहोल्डर निर्भर स्लाइडों पर सम्मिलित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होते हैं। |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर्स में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को डिक्रिमेंट करता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को डिक्रिमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* क्लास [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)