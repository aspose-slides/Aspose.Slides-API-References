---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: प्रस्तुति के सभी फ़ूटर, दिनांक-समय और पेज नंबर प्लेसहोल्डरों के व्यवहार को रखने वाले मैनेजर का प्रतिनिधित्व करता है।
type: docs
weight: 4863
url: /hi/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager क्लास

प्रस्तुति के सभी फ़ूटर, दिनांक-समय और पेज नंबर प्लेसहोल्डरों के व्यवहार को रखने वाला मैनेजर दर्शाता है।

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंट डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउण्ट को घटाता है। |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | सभी दिनांक-समय प्लेसहोल्डर पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स, स्लाइड्स, नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | सभी दिनांक-समय प्लेसहोल्डर की दृश्यमानता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स, स्लाइड्स, नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | सभी फ़ूटर प्लेसहोल्डर पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स, स्लाइड्स, नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | सभी फ़ूटर प्लेसहोल्डर की दृश्यमानता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स, स्लाइड्स, नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | सभी हेडर प्लेसहोल्डर पर टेक्स्ट सेट करता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | सभी हेडर प्लेसहोल्डर की दृश्यमानता बदलता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | सभी पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स, स्लाइड्स, नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | सभी टाइटल स्लाइड्स और पहले लेआउट स्लाइड के लिए फ़ूटर, दिनांक-समय और पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है। टाइटल स्लाइड्स \u2013 पहले लेआउट स्लाइड पर आधारित स्लाइड्स (पहले लेआउट के प्रकार की परवाह किए बिना)। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउण्टर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउण्ट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउण्ट को घटाता है और वापस देता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कनवर्ट करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउण्ट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउण्ट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [BaseHeaderFooterManager](../baseheaderfootermanager/)
* क्लास [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)