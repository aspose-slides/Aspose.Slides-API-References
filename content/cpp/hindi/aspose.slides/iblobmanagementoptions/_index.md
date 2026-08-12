---
title: IBlobManagementOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बाइनरी लार्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात BLOB एक ऑडियो, वीडियो या प्रस्तुति स्वयं हो सकता है। BLOBs के साथ काम करते समय मेमोरी उपयोग को अनुकूलित करने के लिए कई तकनीकों का उपयोग किया जाता है - जो पहले से प्रस्तुति में संग्रहीत था या बाद में प्रोग्रामेटिक रूप से जोड़ा जा सकता है। IBlobManagementOptions का उपयोग करके आप IPresentation इंस्टेंस जीवनकाल के दौरान BLOBs को संभालने के विभिन्न व्यवहार पहलुओं को बदल सकते हैं।
type: docs
weight: 1535
url: /hi/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions क्लास


एक बाइनरी लार्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात BLOB एक ऑडियो, वीडियो या प्रस्तुति स्वयं हो सकता है। BLOBs के साथ काम करते समय मेमोरी उपयोग को अनुकूलित करने के लिए कई तकनीकों का उपयोग किया जाता है - जो पहले से प्रस्तुति में संग्रहीत था या बाद में प्रोग्रामेटिकली जोड़ा जा सकता है। [IBlobManagementOptions](./) का उपयोग करके आप [IPresentation](../ipresentation/) इंस्टेंस जीवनकाल के लिए BLOBs हैंडलिंग से संबंधित विभिन्न व्यवहार पहलुओं को बदल सकते हैं।

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | यह प्रॉपर्टी निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी खपत में काफी कमी आती है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | यह परिभाषित करता है कि सभी BLOBs मेमोरी में अधिकतम कुल आकार (बाइट्स में) कितना हो सकता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँचती है तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग करके आप अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित कर सकते हैं। |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | यह प्रॉपर्टी निर्धारित करती है कि [Presentation](../presentation/) क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन में सुधार करने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को [Presentation](../presentation/) के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका रूट पथ। डिफ़ॉल्ट रूप से [System](../../system/) अस्थायी डायरेक्टरी उपयोग की जाएगी। होस्टिंग प्रक्रिया के पास वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमतियाँ होनी चाहिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट (nullptr) के साथ वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | यह प्रॉपर्टी निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी खपत में काफी कमी आती है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | यह परिभाषित करता है कि सभी BLOBs मेमोरी में अधिकतम कुल आकार (बाइट्स में) कितना हो सकता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँचे तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग करके आप अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित कर सकते हैं। |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | यह प्रॉपर्टी निर्धारित करती है कि [Presentation](../presentation/) क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन में सुधार करने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को [Presentation](../presentation/) के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका रूट पथ। डिफ़ॉल्ट रूप से [System](../../system/) अस्थायी डायरेक्टरी उपयोग की जाएगी। होस्टिंग प्रक्रिया के पास वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमतियाँ होनी चाहिए। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)