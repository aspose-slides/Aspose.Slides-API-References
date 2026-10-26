---
title: IHyperlink
second_title: Aspose.Slides for C++ API संदर्भ
description: एक हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
weight: 2523
url: /hi/aspose.slides/ihyperlink/
---
## IHyperlink क्लास

हाइपरलिंक का प्रतिनिधित्व करता है।

```cpp
class IHyperlink : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | HyperLinkEx की क्रिया का प्रकार लौटाता है। केवल-पढ़ने योग्य [HyperlinkActionType](../hyperlinkactiontype/)। |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | हाइपरलिंक रंग के स्रोत का प्रतिनिधित्व करता है - या तो स्टाइल्स या पोर्शन फ़ॉर्मेट। पढ़ें [HyperlinkColorSource](../hyperlinkcolorsource/)। |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | बाहरी URL निर्दिष्ट करता है। यदि यह प्रॉपर्टी null नहीं है तो TargetSlide प्रॉपर्टी null हो जाएगी। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | एक हाइपरलिंक का प्रतिनिधित्व करता है जो इस भाग के लिए सेट किया गया है, भाग की वास्तविक सामग्री की परवाह किए बिना। |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_History](./get_history/)() | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब इसे कॉल किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | हाइपरलिंक की ध्वनि चलाने का प्रतिनिधित्व करता है। पढ़ें [IAudio](../iaudio/)। |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। पढ़ें **bool**। |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | पैरेंट HTML फ्रेमसेट में लक्ष्य फ्रेम लौटाता है जब वह उपलब्ध हो। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | यदि HyperlinkEx विशिष्ट स्लाइड को लक्ष्य बनाता है तो वह स्लाइड लौटाता है। यदि यह प्रॉपर्टी null नहीं है तो ExternalUrl प्रॉपर्टी null हो जाएगी। केवल-पढ़ने योग्य [ISlide](../islide/)। |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | एक स्ट्रिंग लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ी दिख सकती है। पढ़ें [System::String](../../system/string/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को हैश करने को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित इंस्टेंस का प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | हाइपरलिंक रंग के स्रोत का प्रतिनिधित्व करता है - या तो स्टाइल्स या पोर्शन फ़ॉर्मेट। लिखें [HyperlinkColorSource](../hyperlinkcolorsource/)। |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। लिखें **bool**। |
| virtual void [set_History](./set_history/)(**bool**) | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब इसे कॉल किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। लिखें **bool**। |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | हाइपरलिंक की ध्वनि चलाने का प्रतिनिधित्व करता है। लिखें [IAudio](../iaudio/)। |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। लिखें **bool**। |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | पैरेंट HTML फ्रेमसेट में लक्ष्य फ्रेम लौटाता है जब वह मौजूद हो। लिखें [System::String](../../system/string/)। |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | उस स्ट्रिंग को लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ संबद्ध हो सकती है। लिखें [System::String](../../system/string/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्गुमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)