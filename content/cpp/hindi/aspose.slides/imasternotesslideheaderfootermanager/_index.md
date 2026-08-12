---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for C++ एपीआई रेफ़रेंस
description: ऐसी मैनेजर को दर्शाता है जो मास्टर नोट्स स्लाइड फ़ूटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को रखता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।
type: docs
weight: 2900
url: /hi/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager क्लास


मास्टर नोट्स स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को रखता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | डेट-टाइम प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | फुटर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | हेडर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | पेज नंबर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य-टाइप द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशिष्टता। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशिष्टता। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | स्लाइड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | स्लाइड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | स्लाइड फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | स्लाइड फुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | स्लाइड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | मास्टर नोट्स स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में शामिल हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर नहीं) सेट करता है। कंटेनर में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान शेयर रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* Class [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)