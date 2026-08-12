---
title: BlobManagementOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: ऐसे विकल्पों का प्रतिनिधित्व करता है जो BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकते हैं।
type: docs
weight: 196
url: /hi/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions क्लास

BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है।

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | नए डिफ़ॉल्ट ब्लॉब प्रबंधन विकल्प बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांत का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | यह प्रॉपर्टी निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी की खपत बहुत कम हो जाती है लेकिन फ़ाइलें बनाने की अनुमति आवश्यक होती है। |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | सभी BLOBs द्वारा मेमोरी में घेर सकने वाले अधिकतम कुल आकार (बाइट्स में) को परिभाषित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँच जाती है, तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाई जाती हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए करें। |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | यह प्रॉपर्टी निर्धारित करती है कि [Presentation](../presentation/) क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम - का मालिक बन सकता है या नहीं, इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन [Presentation](../presentation/) के इंस्टेंस के जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) को बदला नहीं जा सकता। |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप से [System](../../system/) अस्थायी डायरेक्टरी उपयोग की जाएगी। होस्टिंग प्रक्रिया को वहाँ फ़ाइलों और फ़ोल्डरों को बनाने की अनुमति होनी चाहिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी अंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | यह प्रॉपर्टी निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी की खपत बहुत कम हो जाती है लेकिन फ़ाइलें बनाने की अनुमति आवश्यक होती है। |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | सभी BLOBs द्वारा मेमोरी में घेर सकने वाले अधिकतम कुल आकार (बाइट्स में) को परिभाषित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँच जाती है, तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाई जाती हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए करें। |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | यह प्रॉपर्टी निर्धारित करती है कि [Presentation](../presentation/) क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम - का मालिक बन सकता है या नहीं, इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को सुधारने में मदद करता है, लेकिन [Presentation](../presentation/) के इंस्टेंस के जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) को बदला नहीं जा सकता। |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप से [System](../../system/) अस्थायी डायरेक्टरी उपयोग की जाएगी। होस्टिंग प्रक्रिया को वहाँ फ़ाइलों और फ़ोल्डरों को बनाने की अनुमति होनी चाहिए। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी अंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IBlobManagementOptions](../iblobmanagementoptions/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)