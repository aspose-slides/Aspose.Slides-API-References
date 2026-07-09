---
title: DocumentProperties
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक प्रस्तुति के गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 2790
url: /hi/aspose.slides/documentproperties/
---
## DocumentProperties वर्ग

एक प्रस्तुति के गुणों का प्रतिनिधित्व करता है।

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [DocumentProperties](documentproperties)() | क्लास [`DocumentProperties`](../documentproperties) का नया उदाहरण आरंभ करता है। |

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | एक एप्लिकेशन के टेम्प्लेट को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | एप्लिकेशन संस्करण लौटाता है। केवल-पढ़ने योग्य String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | प्रस्तुति के लेखक को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | प्रस्तुति की टिप्पणी को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | कंपनी गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | प्रस्तुति के सामग्री प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | कलेक्शन में वास्तव में मौजूद कस्टम प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | प्रस्तुति के निर्मित होने की तिथि लौटाता है। मान UTC में हैं। पढ़ें/लिखें DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या को दर्शाता है। केवल-पढ़ने योग्य IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक्स केवल इस भाग में प्रोड्यूसर द्वारा अपडेट किए गए थे। अगला प्रोड्यूसर इस दस्तावेज़ को खोलते समय इस भाग में निर्दिष्ट नए हाइपरलिंक्स के साथ हाइपरलिंक संबंधों को अपडेट करेगा। पढ़ें/लिखें Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | निर्दिष्ट नाम से जुड़े कस्टम प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | प्रस्तुति के कीवर्ड को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | प्रस्तुति के अंतिम बार प्रिंट किए जाने की तिथि लौटाता है। पढ़ें/लिखें DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | प्रस्तुति के अंतिम संशोधित होने की तिथि लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे विधि [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) विधि सारांश में उदाहरण देखें। |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं, दर्शाता है। हाइपरलिंक्स अपडेट होने का संकेत देने के लिए इस तत्व को **true** सेट करें। हाइपरलिंक्स पुरानी हैं यह दर्शाने के लिए इस तत्व को **false** सेट करें। पढ़ें/लिखें Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | मैनेजर गुण को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | एप्लिकेशन का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | नोट्स वाले प्रस्तुति स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | यदि लागू हो तो दस्तावेज़ में पाए गए पैराग्राफों की कुल संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | प्रस्तुति के इच्छित प्रारूप को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | प्रस्तुति संशोधन संख्या को लौटाता है या सेट करता है। पढ़ें/लिखें Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | दस्तावेज़ थंबनेल के प्रदर्शित मोड को दर्शाता है। दस्तावेज़ थंबनेल को डिस्प्ले के अनुसार स्केल करने के लिए इस तत्व को **true** सेट करें। केवल उन भागों को दिखाने के लिए थंबनेल को क्रॉप करने हेतु इस तत्व को **false** सेट करें जो डिस्प्ले में फिट हों। पढ़ें/लिखें Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ें/लिखें Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | प्रस्तुति के विषय को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | प्रस्तुति का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं हैं बल्कि दस्तावेज़ अनुभागों की अवधारणात्मक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | प्रस्तुति का कुल संपादन समय। पढ़ें/लिखें TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | दस्तावेज़ में उपस्थित शब्दों की कुल संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | सभी निर्मित गुणों को साफ करता है और डिफ़ॉल्ट मान सेट करता है। |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | सभी कस्टम प्रॉपर्टी को हटाता है। |
| [Clone](../../aspose.slides/documentproperties/clone)() | वर्तमान ऑब्जेक्ट को क्लोन करता है |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | वर्तमान ऑब्जेक्ट को क्लोन करता है |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | निर्दिष्ट नाम के साथ कस्टम प्रॉपर्टी की उपस्थिति जाँचता है। |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | निर्दिष्ट इंडेक्स पर कस्टम प्रॉपर्टी का नाम लौटाता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | कस्टम प्रॉपर्टी से नामित बूलियन मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | कस्टम प्रॉपर्टी से नामित DateTime मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | कस्टम प्रॉपर्टी से नामित double मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | कस्टम प्रॉपर्टी से नामित float मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | कस्टम प्रॉपर्टी से नामित पूर्णांक मान प्राप्त करता है। |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | कस्टम प्रॉपर्टी से नामित स्ट्रिंग मान प्राप्त करता है। |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | कस्टम दस्तावेज़ प्रॉपर्टी से संवेदनशीलता लेबल की एक एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को हटाता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | नामित बूलियन कस्टम प्रॉपर्टी सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | नामित DateTime कस्टम प्रॉपर्टी सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | नामित double कस्टम प्रॉपर्टी सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | नामित float कस्टम प्रॉपर्टी सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | नामित पूर्णांक कस्टम प्रॉपर्टी सेट करता है। |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | नामित स्ट्रिंग कस्टम प्रॉपर्टी सेट करता है। |

### उदाहरण

निम्नलिखित उदाहरण PowerPoint प्रस्तुति के निर्मित गुणों तक पहुंच कैसे करे दिखाता है।

```csharp
[C#]
// प्रस्तुति का प्रतिनिधित्व करने वाला Presentation क्लास instantiate करें
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation से जुड़े IDocumentProperties ऑब्जेक्ट का संदर्भ बनाएं
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// बिल्ट-इन प्रॉपर्टीज़ प्रदर्शित करें
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

निम्नलिखित उदाहरण PowerPoint प्रस्तुति के निर्मित गुणों को संशोधित करने का तरीका दिखाता है।

```csharp
[C#]
// प्रस्तुति का प्रतिनिधित्व करने वाला Presentation क्लास instantiate करें
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation से जुड़े IDocumentProperties ऑब्जेक्ट का संदर्भ बनाएं
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// बिल्ट-इन प्रॉपर्टीज़ सेट करें
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// अपनी प्रस्तुति को फ़ाइल में सहेजें
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### अन्य देखें

* इंटरफ़ेस [IDocumentProperties](../idocumentproperties)
* इंटरफ़ेस [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->