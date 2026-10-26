---
title: IDocumentProperties
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक प्रस्तुति की गुणधर्मों का प्रतिनिधित्व करता है।
type: docs
weight: 1977
url: /hi/aspose.slides/idocumentproperties/
---
## IDocumentProperties क्लास

एक प्रस्तुति की गुणधर्मों का प्रतिनिधित्व करता है।

```cpp
class IDocumentProperties : public virtual System::Object
```

## मेथड्स

| मेथड | वर्णन |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | सभी builtIn गुणधर्मों के लिए डिफ़ॉल्ट मान साफ़ करता है और सेट करता है। |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | सभी कस्टम गुणधर्मों को हटाता है। |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | निर्दिष्ट नाम वाले कस्टम गुणधर्म की उपस्थिति की जाँच करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी मान के बराबर नहीं होता, यहाँ तक कि NaN से भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी मान के बराबर नहीं होता, यहाँ तक कि NaN से भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | एक एप्लिकेशन का टेम्पलेट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | ऐप संस्करण लौटाता है। केवल-पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | प्रस्तुति के लेखक को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | प्रस्तुति की श्रेणी लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | प्रस्तुति की टिप्पणियाँ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | कंपनी गुणधर्म लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | प्रस्तुति की सामग्री स्थिति लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | प्रस्तुति के सामग्री प्रकार को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | कलेक्शन में वास्तव में मौजूद कस्टम गुणधर्मों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | प्रस्तुति के निर्माण की तारीख लौटाता है। मान UTC में हैं। पढ़ें [System::DateTime](../../system/datetime/)। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल-पढ़ने योग्य [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)। |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | HyperlinkBase दस्तावेज़ गुणधर्म लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक एक निर्माता द्वारा केवल इस भाग में अद्यतन किए गए थे। अगला निर्माता इस दस्तावेज़ को खोलने पर इस भाग में निर्दिष्ट नए हाइपरलिंक्स के साथ रिलेशनशिप को अपडेट करेगा। पढ़ें **bool**। |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | प्रस्तुति के कीवर्ड्स लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | प्रस्तुति के अंतिम प्रिंट की तिथि लौटाता है। पढ़ें [System::DateTime](../../system/datetime/)। |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह [IPresentation](../ipresentation/) ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे [DocumentProperties](../documentproperties/) इंस्टेंस के माध्यम से बदला जा सकता है जो मेथड [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) द्वारा लौटाया जाता है। कृपया [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) मेथड सारांश में उदाहरण देखें। |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं दर्शाता है। हाइपरलिंक्स अद्यतन होने को संकेत करने के लिए इस तत्व को **true** सेट करें। हाइपरलिंक्स पुराना होने को संकेत करने के लिए इस तत्व को **false** सेट करें। पढ़ें **bool**। |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | प्रबंधक गुणधर्म लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | दस्तावेज़ में मौजूद कुल साउंड या वीडियो क्लिप्स की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | एप्लिकेशन का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_Notes](./get_notes/)() | प्रस्तुति में नोट्स वाले स्लाइडों की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | यदि लागू हो तो दस्तावेज़ में पाई गई कुल पैराग्राफ़ संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | प्रस्तुति के इच्छित फ़ॉर्मेट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | प्रस्तुति संशोधन संख्या लौटाता है। पढ़ें **int32_t**। |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | दस्तावेज़ थंब्नेल का डिस्प्ले मोड दर्शाता है। डिस्प्ले के अनुसार थंब्नेल को स्केल करने के लिए इस तत्व को **true** सेट करें। केवल डिस्प्ले में फिट होने वाले सेक्शंस दिखाने के लिए थंब्नेल को क्रॉप करने के लिए इस तत्व को **false** सेट करें। पढ़ें **bool**। |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। पढ़ें **bool**। |
| virtual **int32_t** [get_Slides](./get_slides/)() | प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | प्रस्तुति का विषय लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | प्रस्तुती का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग दस्तावेज़ भाग नहीं बल्कि दस्तावेज़ सेक्शन की वैचारिक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य [System::ArrayPtr<System::String>](../../system/arrayptr/)। |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | प्रस्तुति के कुल संपादन समय। पढ़ें [System::TimeSpan](../../system/timespan/)। |
| virtual **int32_t** [get_Words](./get_words/)() | दस्तावेज़ में मौजूद कुल शब्दों की संख्या निर्दिष्ट करता है। केवल-पढ़ने योग्य **int32_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | निर्दिष्ट इंडेक्स पर कस्टम गुणधर्म का नाम लौटाता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | कस्टम गुणधर्मों से नामित बूलियन मान प्राप्त करता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | कस्टम गुणधर्मों से नामित इंटेजर मान प्राप्त करता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | कस्टम गुणधर्मों से नामित DateTime मान प्राप्त करता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | कस्टम गुणधर्मों से नामित स्ट्रिंग मान प्राप्त करता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | कस्टम गुणधर्मों से नामित फ़्लोट मान प्राप्त करता है। |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | कस्टम गुणधर्मों से नामित डबल मान प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | कस्टम दस्तावेज़ गुणधर्मों से संवेदनशीलता लेबल्स की एक ऐरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | निर्दिष्ट नाम से जुड़े कस्टम गुणधर्म को लौटाता है। पढ़ें [System::Object](../../system/object/)। |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | निर्दिष्ट नाम से जुड़े कस्टम गुणधर्म को सेट करता है। लिखें [System::Object](../../system/object/)। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपक्लासों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपक्लासों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | value टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | निर्दिष्ट नाम से जुड़े कस्टम गुणधर्म को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | एप्लिकेशन का टेम्पलेट सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | प्रस्तुति का लेखक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | प्रस्तुति की श्रेणी सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | प्रस्तुति की टिप्पणियाँ सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | कंपनी गुणधर्म सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | प्रस्तुति की सामग्री स्थिति सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | प्रस्तुति का कंटेंट टाइप सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में हैं। लिखें [System::DateTime](../../system/datetime/)। |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | HyperlinkBase दस्तावेज़ गुणधर्म सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक एक निर्माता द्वारा केवल इस भाग में अद्यतन किए गए थे। अगला निर्माता इस दस्तावेज़ को खोलने पर इस भाग में निर्दिष्ट नए हाइपरलिंक्स के साथ रिलेशनशिप को अपडेट करेगा। लिखें **bool**। |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | प्रस्तुति के कीवर्ड्स सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | प्रस्तुति के अंतिम प्रिंट की तिथि लौटाता है। लिखें [System::DateTime](../../system/datetime/)। |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह [IPresentation](../ipresentation/) ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे [DocumentProperties](../documentproperties/) इंस्टेंस के माध्यम से बदला जा सकता है जो मेथड [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) द्वारा लौटाया जाता है। कृपया [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) मेथड सारांश में उदाहरण देखें। लिखें। |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | हाइपरलिंक्स ... दर्शाता है। ... लिखें **bool**। |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | प्रबंधक गुणधर्म सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | एप्लिकेशन का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | प्रस्तुति के इच्छित फ़ॉर्मेट को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | प्रस्तुति संशोधन संख्या सेट करता है। लिखें **int32_t**। |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | दस्तावेज़ थंब्नेल का डिस्प्ले मोड दर्शाता है। डिस्प्ले के अनुसार थंब्नेल को स्केल करने के लिए इस तत्व को **true** सेट करें। केवल डिस्प्ले में फिट होने वाले सेक्शंस दिखाने के लिए थंब्नेल को क्रॉप करने के लिए इस तत्व को **false** सेट करें। लिखें **bool**। |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। लिखें **bool**। |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | प्रस्तुति का विषय सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | प्रस्तुति का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | प्रस्तुति के कुल संपादन समय। लिखें [System::TimeSpan](../../system/timespan/)। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | नामित बूलियन कस्टम गुणधर्म सेट करता है। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | नामित इंटेजर कस्टम गुणधर्म सेट करता है। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | नामित DateTime कस्टम गुणधर्म सेट करता है। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | नामित स्ट्रिंग कस्टम गुणधर्म सेट करता है। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | नामित फ़्लोट कस्टम गुणधर्म सेट करता है। |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | नामित डबल कस्टम गुणधर्म सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'tवीं टेम्पलेट आर्गुमेंट को वीक पॉइंटर (शेअर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेअर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेअर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेअर्ड रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)