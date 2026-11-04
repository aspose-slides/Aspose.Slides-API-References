---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रस्तुति की गुणधर्मों का प्रतिनिधित्व करता है।
type: docs
weight: 5730
url: /hi/aspose.slides/idocumentproperties/
---
## IDocumentProperties इंटरफ़ेस

एक प्रस्तुति की विशेषताओं का प्रतिनिधित्व करता है।

```csharp
public interface IDocumentProperties
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | एक एप्लिकेशन का टेम्पलेट लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | एप्लिकेशन संस्करण लौटाता है। केवल पढ़ने योग्य String। |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | प्रस्तुति के लेखक को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | प्रस्तुति की टिप्पणियों को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | कंपनी गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | प्रस्तुति की सामग्री प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | संग्रह में वास्तविक रूप से मौजूद कस्टम गुणों की संख्या लौटाता है। केवल पढ़ने योग्य Int32। |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में होते हैं। पढ़ें/लिखें DateTime। |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल पढ़ने योग्य IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | एक या अधिक हाइपरलिंक इस भाग में केवल इस भाग के निर्माता द्वारा अपडेट किए गए थे। अगला निर्माता जो इस दस्तावेज़ को खोलेगा, लिंक संबंधों को इस भाग में निर्दिष्ट नए हाइपरलिंक से अपडेट करेगा। पढ़ें/लिखें Boolean। |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | निर्दिष्ट नाम के साथ जुड़े कस्टम गुण को लौटाता है या सेट करता है। पढ़ें/लिखें Object। |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | प्रस्तुति के कीवर्ड लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | प्रस्तुति के अंतिम प्रिंट होने की तिथि लौटाता है। पढ़ें/लिखें DateTime। |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | प्रस्तुति के अंतिम संशोधित होने की तारीख लौटाता है। मान UTC में होते हैं। Presentation.DocumentProperties के मामले में केवल पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे मेथड [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) मेथड सारांश में उदाहरण देखें। |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | दर्शाता है कि दस्तावेज़ में हाइपरलिंक अपडेट हैं या नहीं। हाइपरलिंक अपडेट हैं यह दर्शाने के लिए इस तत्व को **true** सेट करें। हाइपरलिंक पुरानी हैं यह दर्शाने के लिए इस तत्व को **false** सेट करें। पढ़ें/लिखें Boolean। |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | मैनेजर गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | एप्लिकेशन का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | प्रस्तुति में नोट्स वाले स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | यदि लागू हो तो दस्तावेज़ में पाए गए पैराग्राफ़ की कुल संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | प्रस्तुति के इरादा फ़ॉर्मेट को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | प्रस्तुति संशोधन संख्या लौटाता है या सेट करता है। पढ़ें/लिखें Int32। |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। डिस्प्ले पर थंबनेल को स्केल करने के लिए इस तत्व को **true** सेट करें। डिस्प्ले पर केवल वह भाग दिखाने के लिए थंबनेल को क्रॉप करने के लिए इस तत्व को **false** सेट करें। पढ़ें/लिखें Boolean। |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ें/लिखें Boolean। |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | प्रस्तुति का विषय लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | प्रस्तुति का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं बल्कि दस्तावेज़ अनुभागों के अवधारणात्मक प्रतिनिधित्व हैं। केवल पढ़ने योग्य string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | प्रस्तुति का कुल संपादन समय। पढ़ें/लिखें TimeSpan। |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | दस्तावेज़ में सम्मिलित कुल शब्दों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | सभी builtIn गुणों के लिए डिफ़ॉल्ट मान साफ़ करता है और सेट करता है। |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | सभी कस्टम गुणों को हटाता है। |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | निर्दिष्ट नाम वाले कस्टम गुण की उपस्थिति जाँचता है। |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | निर्दिष्ट अनुक्रमणिका पर कस्टम गुण का नाम लौटाता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | कस्टम गुणों से निर्दिष्ट बूलियन मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | कस्टम गुणों से निर्दिष्ट DateTime मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | कस्टम गुणों से निर्दिष्ट डबल मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | कस्टम गुणों से निर्दिष्ट फ़्लोट मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | कस्टम गुणों से निर्दिष्ट पूर्णांक मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | कस्टम गुणों से निर्दिष्ट स्ट्रिंग मान प्राप्त करता है। |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | कस्टम दस्तावेज़ गुणों से संवेदनशीलता लेबल की श्रृंखला प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | निर्दिष्ट नाम से जुड़े कस्टम गुण को हटाता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | निर्दिष्ट बूलियन कस्टम गुण सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | निर्दिष्ट DateTime कस्टम गुण सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | निर्दिष्ट डबल कस्टम गुण सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | निर्दिष्ट फ़्लोट कस्टम गुण सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | निर्दिष्ट पूर्णांक कस्टम गुण सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | निर्दिष्ट स्ट्रिंग कस्टम गुण सेट करता है। |

### देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->