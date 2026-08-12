---
title: BoxedValueBase
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक बेस क्लास जो एक इंटरफ़ेस को परिभाषित करती है और बॉक्स्ड वैल्यू का प्रतिनिधित्व करने वाली अवैतनिक क्लास के कुछ मूलभूत मेथड्स को लागू करती है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 131
url: /hi/system/boxedvaluebase/
---
## BoxedValueBase क्लास

एक बेस क्लास जो एक इंटरफ़ेस को परिभाषित करता है और बॉक्स्ड वैल्यू का प्रतिनिधित्व करने वाली अवैतनिक क्लास के कुछ मूलभूत मेथड्स को लागू करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स को तर्क के रूप में पास करने के लिए करें।

```cpp
class BoxedValueBase : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समतुल्य। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | वस्तु का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समतुल्य। |
| virtual [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए बॉक्स्ड वैल्यू के प्रकार को दर्शाने वाला मान लौटाता है। |
| virtual **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए बॉक्स्ड को 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित टाइप का एक इंस्टैंस दर्शाती है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| virtual **bool** [IsBoxedEnum](./isboxedenum/)() | निर्धारित करता है कि वर्तमान वस्तु enum प्रकार का बॉक्स्ड वैल्यू दर्शाती है या नहीं। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | निर्दिष्ट एन्यूमरेशन के नाम के साथ निर्दिष्ट नाम वाले एन्यूमरेशन कॉन्स्टेंट के मान को बॉक्स करता है। एक पैरामीटर यह दर्शाता है कि एन्यूमरेशन कॉन्स्टेंट के नाम को निर्दिष्ट करने वाली स्ट्रिंग की व्याख्या करते समय केस को अनदेखा किया जाना चाहिए या नहीं। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | निर्दिष्ट एन्यूमरेशन के नाम के साथ निर्दिष्ट नाम वाले एन्यूमरेशन कॉन्स्टेंट के मान को बॉक्स करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामलों के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग मामलों के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [System::String](../string/) [ToString](./tostring/)(const [System::String](../string/)\&) const | निर्दिष्ट फ़ॉर्मेट स्ट्रिंग का उपयोग करके बॉक्स्ड वस्तु को स्ट्रिंग में परिवर्तित करता है। |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](../object/tostring/) मेथड का समतुल्य। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## अन्य देखें

* क्लास [Object](../object/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)