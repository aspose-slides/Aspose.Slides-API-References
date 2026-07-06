---
title: Presentation
second_title: Aspose.Sildes for .NET API संदर्भ
description: Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।
type: docs
weight: 9590
url: /hi/aspose.slides/presentation/
---
## Presentation क्लास

Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।

```csharp
public sealed class Presentation : IPresentation
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Presentation](presentation#constructor)() | यह कंस्ट्रक्टर नई प्रस्तुति को प्रारम्भ से बनाता है। निर्मित प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_1)(LoadOptions) | यह कंस्ट्रक्टर नई प्रस्तुति को प्रारम्भ से बनाता है। निर्मित प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_2)(Stream) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए मुख्य तंत्र है। |
| [Presentation](presentation#constructor_4)(string) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | यह कंस्ट्रक्टर मौजूदा प्रस्तुति को पढ़ने के लिए मुख्य तंत्र है। |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे प्रस्तुति की सामग्री पढ़ी जाती है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | प्रस्तुति में सभी कस्टम डेटा भागों को लौटाता है। केवल पढ़ने योग्य [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों के संग्रह को लौटाता है। केवल पढ़ने योग्य [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल पढ़ने योग्य [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | तिथि और समय को लौटाता है या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। यह Presentation ऑब्जेक्ट के निर्माण का समय है। पढ़ने/लिखने योग्य DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | प्रस्तुति के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली को लौटाता है। केवल पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | प्रस्तुति को साइन करने के लिए उपयोग किए गए हस्ताक्षरों के संग्रह को लौटाता है। केवल पढ़ने योग्य [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | DocumentProperties ऑब्जेक्ट को लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल पढ़ने योग्य [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | प्रस्तुति में पहले स्लाइड नंबर का प्रतिनिधित्व करता है। |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | फ़ॉन्ट मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | वास्तविक HeaderFooter मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | सभी प्रस्तुति स्लाइडों (मास्टर, लेआउट, नोट्स स्लाइड नहीं) में मौजूद सभी हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | प्रस्तुति में सभी छवियों के संग्रह को लौटाता है। केवल पढ़ने योग्य [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। केवल पढ़ने योग्य [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | हैंडआउट मास्टर मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | नोट्स मास्टर मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। केवल पढ़ने योग्य [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | मास्टर थीम को लौटाता है। केवल पढ़ने योग्य [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | नोट्स स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | इस प्रस्तुति के अनुमति प्रबंधक को प्राप्त करता है। केवल पढ़ने योग्य [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | प्रस्तुति में सभी स्लाइड सेक्शन की सूची लौटाता है। केवल पढ़ने योग्य [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल के संग्रह को लौटाता है। केवल पढ़ने योग्य [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | प्रस्तुति में सभी स्लाइडों की सूची लौटाता है। केवल पढ़ने योग्य [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | प्रस्तुति के स्लाइड शो सेटिंग्स को लौटाता है। |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | इस बात की जानकारी देता है कि प्रस्तुति किस फॉर्मेट से लोड की गई थी। केवल पढ़ने योग्य [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों के संग्रह को लौटाता है। केवल पढ़ने योग्य [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | प्रस्तुति-व्यापी व्यू प्रॉपर्टीज़ को प्राप्त करता है। केवल पढ़ने योग्य [`IViewProperties`](../iviewproperties). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | प्रस्तुति की सभी स्लाइडों के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | कस्टम स्केलिंग के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है। |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट रंग के साथ नमूना टेक्स्ट के सभी मिलानों को हाईलाइट करता है। |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | सभी स्लाइडों में सभी स्वीकार्य आकारों के सभी पैराग्राफ में समान स्वरूप के रन को जोड़ता है। |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | प्रस्तुति की सभी स्लाइडों को XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | निर्दिष्ट फ़ॉर्मेट में प्रस्तुति की सभी स्लाइडों को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | निर्दिष्ट फ़ॉर्मेट के साथ प्रस्तुति की सभी स्लाइडों को फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रस्तुति की सभी स्लाइडों को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | निर्दिष्ट स्लाइडों को पेज नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint Presentation कैसे बनाएं।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation())
{
    // पहली स्लाइड प्राप्त करें
    ISlide slide = presentation.Slides[0];
    // लाइन प्रकार का ऑटोशेप जोड़ें
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// प्रस्तुति फ़ाइल को सहेजें।
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

निम्न उदाहरण दिखाता है कि Presentation को कैसे खोलें और सहेजें।

```csharp
[C#]
// Presentation में कोई भी समर्थित फ़ाइल लोड करें, जैसे ppt, pptx, odp आदि।
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// प्रस्तुति फ़ाइल को सहेजें।
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* इंटरफ़ेस [IPresentation](../ipresentation)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->