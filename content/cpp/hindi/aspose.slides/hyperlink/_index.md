---
title: Hyperlink
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
weight: 1236
url: /hi/aspose.slides/hyperlink/
---
## Hyperlink क्लास

Represents a hyperlink.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## विधियाँ

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि दो [Hyperlink](./) इंस्टेंस समान हैं या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल अंतरिक प्रयोजनों के लिए। |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | [Hyperlink](./) की क्रिया का प्रकार लौटाता है। केवल-पढ़ने योग्य [HyperlinkActionType](../hyperlinkactiontype/)। |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो शैली या भाग स्वरूप। केवल पढ़ें [HyperlinkColorSource](../hyperlinkcolorsource/)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | एक हाइपरलिंक लौटाता है जो शो को समाप्त करता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | बाहरी URL निर्दिष्ट करता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | एक हाइपरलिंक दर्शाता है जो इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को ध्यान में रखे। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | प्रेजेंटेशन की पहली स्लाइड के लिए हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं निर्धारित करता है। पढ़ें **bool**। |
| **bool** [get_History](./get_history/)() override | जब पैरेंट हाइपरलिंक को बुलाया जाता है तो उसके टारगेट को देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं निर्धारित करता है। पढ़ें **bool**। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | प्रेजेंटेशन की अंतिम स्लाइड के लिए हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | अंतिम देखी गई स्लाइड के लिए हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। [AudioFrame](../audioframe/) और [VideoFrame](../videoframe/) में उपयोग किया जाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | अगली स्लाइड के लिए हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | एक विशेष "do nothing" हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | पिछली स्लाइड के लिए हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](./)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | हाइपरलिंक की प्ले हो रही ध्वनि दर्शाता है। पढ़ें [IAudio](../iaudio/)। |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं निर्धारित करता है। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | जब मौजूद हो तो पैरेंट हाइपरलिंक के टारगेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ें/लिखें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | यदि [Hyperlink](./) विशेष स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है। केवल-पढ़ने योग्य [ISlide](../islide/)। |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | एक स्ट्रिंग लौटाता है जिसे उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ा दिखाया जा सकता है। पढ़ें [System::String](../../system/string/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसे डेटा स्ट्रक्चर में उपयोग के उपयुक्त है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | हाइपरलिंक का एक उदाहरण बनाता है। |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | एक हाइपरलिंक का उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर इंगित करता है। नोट: बनाया गया हाइपरलिंक उसी प्रेज़ेंटेशन के किसी ऑब्जेक्ट को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा। |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | एक हाइपरलिंक को स्रोत के रूप में उपयोग करके हाइपरलिंक का उदाहरण बनाता है, द्वितीयक गुणों को ओवरराइड करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी अंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो शैली या भाग स्वरूप। लिखें [HyperlinkColorSource](../hyperlinkcolorsource/)। |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_History](./set_history/)(**bool**) override | पैरेंट हाइपरलिंक के टारगेट को बुलाए जाने पर देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | हाइपरलिंक की प्ले हो रही ध्वनि दर्शाता है। लिखें [IAudio](../iaudio/)। |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | जब मौजूद हो तो पैरेंट हाइपरलिंक के टारगेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ें/लिखें [System::String](../../system/string/)। |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | एक स्ट्रिंग लौटाता है जिसे उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ा दिखाया जा सकता है। लिखें [System::String](../../system/string/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'w'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी अंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IHyperlink](../ihyperlink/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)