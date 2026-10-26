---
title: DocumentProperties
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक प्रस्तुति की विशेषताओं का प्रतिनिधित्व करता है।
type: docs
weight: 794
url: /hi/aspose.slides/documentproperties/
---
## DocumentProperties क्लास

एक प्रस्तुति की विशेषताओं का प्रतिनिधित्व करता है।

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | सभी builtIn गुणों के लिए डिफ़ॉल्ट मान साफ़ करता है और सेट करता है। |
| void [ClearCustomProperties](./clearcustomproperties/)() override | सभी कस्टम गुण हटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की प्रतिलिपि बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | वर्तमान ऑब्जेक्ट की प्रतिलिपि बनाता है। |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | निर्दिष्ट नाम वाले एक कस्टम गुण की उपस्थिति जाँचता है। |
|  [DocumentProperties](./documentproperties/)() | [DocumentProperties](./) क्लास का नया उदाहरण इनिशियलाइज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग कर करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना की नकल करता है जिसमें दो NaN को सम-मान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना की नकल करता है जिसमें दो NaN को सम-मान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | एक एप्लिकेशन का टेम्पलेट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | एप्लिकेशन संस्करण लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | प्रस्तुति के लेखक को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | प्रस्तुति की श्रेणी लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | प्रस्तुति की टिप्पणी लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | कंपनी गुण लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | प्रस्तुति की कंटेंट स्थिति लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | प्रस्तुति की कंटेंट प्रकार लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | एक संग्रह में वास्तव में मौजूद कस्टम गुणों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में हैं। पढ़ें [System::DateTime](../../system/datetime/)। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल-पढ़ने योग्य [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)। |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | HyperlinkBase दस्तावेज़ गुण लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक किसी निर्माता द्वारा केवल इस भाग में अद्यतन किए गए थे। इस दस्तावेज़ को खोलने वाला अगला निर्माता इस भाग में निर्दिष्ट नए हाइपरलिंक्स के साथ हाइपरलिंक संबंधों को अद्यतन करेगा। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | प्रस्तुति की कीवर्ड्स लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | प्रस्तुति की अंतिम प्रिंट तिथि लौटाता है। पढ़ें [System::DateTime](../../system/datetime/)। |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) की स्थिति में केवल-पढ़ने योग्य (क्योंकि यह [IPresentation](../ipresentation/) ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे [DocumentProperties](./) इंस्टेंस द्वारा बदल सकते हैं जो मेथड [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) से प्राप्त होता है। कृपया [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) मेथड सारांश में उदाहरण देखें। |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | निर्दिष्ट करता है कि दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं। हाइपरलिंक्स अद्यतन होने को दर्शाने के लिए इस तत्व को **true** सेट करें। हाइपरलिंक्स पुराने हैं को दर्शाने के लिए इस तत्व को **false** सेट करें। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | प्रबंधक गुण लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | एप्लिकेशन का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **int32_t** [get_Notes](./get_notes/)() override | नोट्स वाले स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | दस्तावेज़ में पाए गए पैराग्राफ़ की कुल संख्या लौटाता है (यदि लागू हो)। केवल-पढ़ने योग्य **int32_t**। |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | प्रस्तुति के इच्छित फ़ॉर्मेट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | प्रस्तुति संशोधन संख्या लौटाता है। पढ़ें **int32_t**। |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | दस्तावेज़ थंबनेल के प्रदर्शित मोड को दर्शाता है। थंबनेल को डिस्प्ले के अनुसार स्केल करने के लिए इस तत्व को **true** सेट करें। केवल उन भागों को दिखाने के लिए थंबनेल को क्रॉप करने हेतु इस तत्व को **false** सेट करें जो डिस्प्ले में फिट होते हैं। पढ़ें **bool**। |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ें **bool**। |
| **int32_t** [get_Slides](./get_slides/)() override | प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | प्रस्तुति का विषय लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | प्रस्तुति का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं बल्कि दस्तावेज़ अनुभागों के वैचारिक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य [System::ArrayPtr<System::String>](../../system/arrayptr/)। |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | प्रस्तुति का कुल संपादन समय। पढ़ें [System::TimeSpan](../../system/timespan/)। |
| **int32_t** [get_Words](./get_words/)() override | दस्तावेज़ में शामिल शब्दों की कुल संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर कस्टम गुण का नाम लौटाता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | कस्टम गुणों से नामित बूलियन मान प्राप्त करता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | कस्टम गुणों से नामित इंटेजर मान प्राप्त करता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | कस्टम गुणों से नामित DateTime मान प्राप्त करता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | कस्टम गुणों से नामित स्ट्रिंग मान प्राप्त करता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | कस्टम गुणों से नामित फ्लोट मान प्राप्त करता है। |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | कस्टम गुणों से नामित डबल मान प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | कस्टम दस्तावेज़ गुणों से संवेदनशीलता लेबल की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | निर्दिष्ट नाम से जुड़ा कस्टम गुण लौटाता है। पढ़ें [System::Object](../../system/object/)। |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट नाम से जुड़ा कस्टम गुण सेट करता है। लिखें [System::Object](../../system/object/)। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत कक्षा। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत कक्षा। |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | निर्दिष्ट नाम वाले कस्टम गुण को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | एप्लिकेशन का टेम्पलेट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | प्रस्तुति का लेखक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | प्रस्तुति की श्रेणी सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | प्रस्तुति की टिप्पणी सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | कंपनी गुण सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | प्रस्तुति की कंटेंट स्थिति सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | प्रस्तुति की कंटेंट प्रकार सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में हैं। लिखें [System::DateTime](../../system/datetime/)। |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | HyperlinkBase दस्तावेज़ गुण सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक किसी निर्माता द्वारा केवल इस भाग में अद्यतन किए गए थे। इस दस्तावेज़ को खोलने वाला अगला निर्माता इस भाग में निर्दिष्ट नए हाइपरलिंक्स के साथ हाइपरलिंक संबंधों को अद्यतन करेगा। लिखें **bool**। |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | प्रस्तुति की कीवर्ड्स सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | प्रस्तुति की अंतिम प्रिंट तिथि लौटाता है। लिखें [System::DateTime](../../system/datetime/)। |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) की स्थिति में केवल-पढ़ने योग्य (क्योंकि यह [IPresentation](../ipresentation/) ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे [DocumentProperties](./) इंस्टेंस द्वारा बदला जा सकता है जो मेथड [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) से प्राप्त होता है। कृपया [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) मेथड सारांश में उदाहरण देखें। |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | निर्दिष्ट करता है कि दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं। हाइपरलिंक्स अद्यतन होने को दर्शाने के लिए इस तत्व को **true** सेट करें। हाइपरलिंक्स पुराने हैं को दर्शाने के लिए इस तत्व को **false** सेट करें। लिखें **bool**। |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | प्रबंधक गुण सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | एप्लिकेशन का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | प्रस्तुति के इच्छित फ़ॉर्मेट को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | प्रस्तुति संशोधन संख्या सेट करता है। लिखें **int32_t**। |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | दस्तावेज़ थंबनेल के प्रदर्शित मोड को दर्शाता है। थंबनेल को डिस्प्ले के अनुसार स्केल करने के लिए इस तत्व को **true** सेट करें। केवल उन भागों को दिखाने के लिए थंबनेल को क्रॉप करने हेतु इस तत्व को **false** सेट करें जो डिस्प्ले में फिट होते हैं। लिखें **bool**। |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। लिखें **bool**। |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | प्रस्तुति का विषय सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | प्रस्तुति का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | प्रस्तुति का कुल संपादन समय। लिखें [System::TimeSpan](../../system/timespan/)। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | नामित बूलियन कस्टम गुण सेट करता है। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | नामित इंटेजर कस्टम गुण सेट करता है। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | नामित DateTime कस्टम गुण सेट करता है। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | नामित स्ट्रिंग कस्टम गुण सेट करता है। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | नामित फ्लोट कस्टम गुण सेट करता है। |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | नामित डबल कस्टम गुण सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटरों को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

निम्नलिखित उदाहरण दिखाता है कि PowerPoint [Presentation](../presentation/) की अंतर्निहित प्रॉपर्टीज़ तक कैसे पहुँचें।

```cpp
// प्रस्तुति को दर्शाने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
निम्नलिखित उदाहरण दिखाता है कि PowerPoint [Presentation](../presentation/) की अंतर्निहित प्रॉपर्टीज़ को कैसे संशोधित करें।

```cpp
// Presentation क्लास का उदाहरण बनाएं जो प्रस्तुति को दर्शाता है
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Presentation से जुड़े IDocumentProperties ऑब्जेक्ट का रेफ़रेंस बनाएं
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Set the builtin properties
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// अपनी प्रस्तुति को एक फ़ाइल में सहेजें
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## देखें भी

* Class [IDocumentProperties](../idocumentproperties/)
* Class [IGenericCloneable](../igenericcloneable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)