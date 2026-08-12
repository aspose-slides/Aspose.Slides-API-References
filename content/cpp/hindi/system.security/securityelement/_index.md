---
title: SecurityElement
second_title: Aspose.Slides for C++ API संदर्भ
description: "सुरक्षा ऑब्जेक्ट को एन्कोड करने के लिए XML ऑब्जेक्ट मॉडल। लागू नहीं किया गया है। इस वर्ग की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि इससे रनटाइम त्रुटियाँ और/या ऐसर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों में आर्ग्युमेंट के रूप में पास करें।"
type: docs
weight: 40
url: /hi/system.security/securityelement/
---
## SecurityElement वर्ग

XML ऑब्जेक्ट को एन्कोड करने के लिए सुरक्षा ऑब्जेक्ट का ऑब्जेक्ट मॉडल। लागू नहीं किया गया है। इस वर्ग की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या ऐसर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को आर्ग्युमेंट के रूप में फ़ंक्शनों को पास करें।

```cpp
class SecurityElement : public System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | टैग में विशेषता जोड़ता है। |
| void [AddChild](./addchild/)([SecurityElement](./)) | चाइल्ड टैग जोड़ता है। |
| [String](../../system/string/) [Attribute](./attribute/)(const [String](../../system/string/)\&) | विशेषता मान प्राप्त करता है। |
| [SecurityElement](./) [Copy](./copy/)() | टैग को क्लोन करता है। |
| **bool** [Equal](./equal/)([SecurityElement](./)) | पैरामीटर की समानता जाँचता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | XML स्ट्रिंग में वर्णों को एस्केप करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static [SecurityElement](./) [FromString](./fromstring/)(const [String](../../system/string/)\&) | XML कोड से तत्व बनाता है। |
| [System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\> [get_Attributes](./get_attributes/)() | टैग विशेषताएँ प्राप्त करता है। |
| [System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\> [get_Children](./get_children/)() | टैग चाइल्ड ऑब्जेक्ट्स प्राप्त करता है। |
| [String](../../system/string/) [get_Tag](./get_tag/)() | टैग नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Text](./get_text/)() | टैग के अंदरूनी पाठ को प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| static **bool** [IsValidAttributeName](./isvalidattributename/)(const [String](../../system/string/)\&) | जाँचता है कि विशेषता नाम वैध है या नहीं। |
| static **bool** [IsValidAttributeValue](./isvalidattributevalue/)(const [String](../../system/string/)\&) | जाँचता है कि विशेषता मान वैध है या नहीं। |
| static **bool** [IsValidTag](./isvalidtag/)(const [String](../../system/string/)\&) | जाँचता है कि टैग वैध है या नहीं। |
| static **bool** [IsValidText](./isvalidtext/)(const [String](../../system/string/)\&) | जाँचता है कि टेक्स्ट वैध है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउण्टर को घटाता है। |
| [SecurityElement](./) [SearchForChildByTag](./searchforchildbytag/)(const [String](../../system/string/)\&) | नाम द्वारा चाइल्ड टैग प्राप्त करता है। |
| [String](../../system/string/) [SearchForTextOfTag](./searchfortextoftag/)(const [String](../../system/string/)\&) | टैग नाम द्वारा चाइल्ड टैग के आंतरिक टेक्स्ट को प्राप्त करता है। |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
| void [set_Attributes](./set_attributes/)([System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>) | टैग विशेषताएँ सेट करता है। |
| void [set_Children](./set_children/)([System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\>) | टैग चाइल्ड ऑब्जेक्ट्स सेट करता है। |
| void [set_Tag](./set_tag/)(const [String](../../system/string/)\&) | टैग नाम सेट करता है। |
| void [set_Text](./set_text/)(const [String](../../system/string/)\&) | टैग के अंदरूनी टेक्स्ट को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउण्टर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउण्टर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउण्टर को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | टैग को स्ट्रिंग में परिवर्तित करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउण्टर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउण्टर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* वर्ग [Object](../../system/object/)
* नामस्थान [System::Security](../)
* लाइब्रेरी [Aspose.Slides](../../)