---
title: Object
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बेस क्लास जो C# में System.Object क्लास के उपलब्ध मेथड्स के उपयोग को सक्षम करती है। अनुवादित वातावरण में उपयोग की जाने वाली सभी गैर-त्रिवियल क्लासेज़ को इसे विरासत में लेना चाहिए।
type: docs
weight: 1132
url: /hi/system/object/
---
## ऑब्जेक्ट क्लास

Base क्लास जो C# में [System.Object](./) क्लास के उपलब्ध मेथड्स के उपयोग को सक्षम करता है। अनुवादित माहौल में उपयोग की जाने वाली सभी गैर-त्रिवियल क्लासेज़ को इसे उत्तराधिकार करना चाहिए।

```cpp
class Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](./equals/) सेमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | C# [Object.GetHashCode()](./gethashcode/) मेथड का अनुकूल रूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](./gettype/) कॉल का अनुकूल रूप। |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनुकूल रूप। |
| void [Lock](./lock/)() | C# lock() स्टेटमेंट की लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | C# [Object.MemberwiseClone()](./memberwiseclone/) मेथड का अनुकूल रूप। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](./object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](./object/)([Object](./) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/) की स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/) की स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](./sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](./tostring/) मेथड का अनुकूल रूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | C# typeof([System.Object](./)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](./unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](./weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](./~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ptr](./ptr/) | स्मार्ट पॉइंटर टाइप का उपनाम। |

## टिप्पणियाँ

C# [System.Object](./) क्लास में उपलब्ध मेथड्स के साथ-साथ, यह अनुवादित कोड माहौल के लिए विशेष कुछ अवधारणाओं के समर्थन को भी सक्षम करता है। इसमें स्मार्ट पॉइंटर क्लासेज़ ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) द्वारा उपयोग किया गया रेफ़रेंस काउंटिंग और मेमोरी मैनेजमेंट, डिबग आदि से संबंधित अन्य सेवाएँ शामिल हैं।

प्रत्येक [Object](./) में दो रेफ़रेंस काउंटर होते हैं: साझा रेफ़रेंस काउंटर और कमजोर रेफ़रेंस काउंटर। कमजोर रेफ़रेंस काउंटर हमेशा [Object](./) स्वयं के बजाय एक अलग डेटा स्ट्रक्चर में संग्रहीत रहता है, जिससे कमजोर पॉइंटर्स रेफ़रेंस किए गए ऑब्जेक्ट को ओवरलाइव कर सकते हैं। स्मार्ट रेफ़रेंस काउंटर या तो ऑब्जेक्ट स्वयं में या उसी अलग स्ट्रक्चर में संग्रहीत रहता है, यह ENABLE_EXTERNAL_REFCOUNT मैक्रो स्थिति पर निर्भर करता है। डिफ़ॉल्ट रूप से, यह डिबग बिल्ड्स में सक्षम और रिलीज़ बिल्ड्स में निष्क्रिय रहता है। यदि स्मार्ट पॉइंटर काउंटर ऑब्जेक्ट स्वयं में संग्रहीत है, तो अलग डेटा स्ट्रक्चर केवल तभी बनाया जाता है जब ऑब्जेक्ट के लिए कमजोर पॉइंटर मौजूद हों। अन्यथा, यह ऑब्जेक्ट के साथ ही बनाया जाता है।

सभी स्मार्ट पॉइंटर्स इन दो रेफ़रेंस काउंटर्स का उपयोग करते हैं और केवल एक ही स्वामित्व समूह में योगदान देते हैं।

यदि [Object](./) सबक्लास को स्टैक पर बनाया जाता है, तो उसके लिए कोई स्मार्ट पॉइंटर नहीं बनाया जा सकता, अन्यथा स्टैक डिलीशन समस्या उत्पन्न होती है।

यह प्रकार या तो स्टैक में वैल्यू टाइप के रूप में या हीप में [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जा सकता है। एक बार ऑब्जेक्ट आवंटित हो जाने पर, इन दो उपयोग मामलों को कभी न मिलाएँ: [SmartPtr](../smartptr/) पॉइंटर्स को स्टैक-एलोकेटेड ऑब्जेक्ट्स पर रखना कड़ाई से प्रतिबंधित है।

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)