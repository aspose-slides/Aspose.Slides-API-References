---
title: Presentation
second_title: Aspose.Sildes for .NET API संदर्भ
description: Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।
type: docs
weight: 9590
url: /hi/aspose.slides/presentation/
---
## Presentation क्लास

Microsoft PowerPoint प्रस्तुति को दर्शाता है।

```csharp
public sealed class Presentation : IPresentation
```

## निर्माताओं

| नाम | विवरण |
| --- | --- |
| [Presentation](presentation#constructor)() | यह निर्माता नई प्रस्तुति को शून्य से बनाता है। बनी प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_1)(LoadOptions) | यह निर्माता नई प्रस्तुति को शून्य से बनाता है। बनी प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_2)(Stream) | यह निर्माता मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है। |
| [Presentation](presentation#constructor_4)(string) | यह निर्माता स्रोत फ़ाइल पथ से प्रस्तुति की सामग्री पढ़ता है। |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | यह निर्माता मौजूदा प्रस्तुति को पढ़ने के लिए प्राथमिक तंत्र है। |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | यह निर्माता स्रोत फ़ाइल पथ से प्रस्तुति की सामग्री पढ़ता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | प्रस्तुति में सभी कस्टम डेटा भाग लौटाता है। केवल-पठनीय [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | प्रस्तुति में सभी एंबेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पठनीय [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | टिप्पणी लेखकों का संग्रह लौटाता है। केवल-पठनीय [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | datetime फ़ील्ड की सामग्री को बदलने के लिए तिथि और समय लौटाता या सेट करता है। यह प्रस्तुति ऑब्जेक्ट के निर्माण की तिथि-समय है। पढ़ें/लिखें DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | प्रस्तुति के कस्टम डेटा को लौटाता है। केवल-पठनीय [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पठनीय [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | प्रस्तुति को हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पठनीय [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक एवं कस्टम दस्तावेज़ गुण होते हैं। केवल-पठनीय [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | प्रस्तुति में पहली स्लाइड संख्या को दर्शाता है। |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | फ़ॉन्ट प्रबंधक को लौटाता है। केवल-पठनीय [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | वास्तविक HeaderFooter प्रबंधक को लौटाता है। केवल-पठनीय [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | सभी स्लाइडों (मास्टर, लेआउट, नोट्स स्लाइड नहीं) में मौजूद सभी हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पठनीय [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | प्रस्तुति में सभी चित्रों का संग्रह लौटाता है। केवल-पठनीय [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। केवल-पठनीय [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | हैंडआउट मास्टर प्रबंधक को लौटाता है। केवल-पठनीय [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | नोट्स मास्टर प्रबंधक को लौटाता है। केवल-पठनीय [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। केवल-पठनीय [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | मास्टर थीम को लौटाता है। केवल-पठनीय [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | नोट्स स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल-पठनीय [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | इस प्रस्तुति के लिए अनुमतियों के प्रबंधक को प्राप्त करता है। केवल-पठनीय [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | प्रस्तुति में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पठनीय [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल का संग्रह लौटाता है। केवल-पठनीय [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | प्रस्तुति में परिभाषित सभी स्लाइडों की सूची लौटाता है। केवल-पठनीय [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | प्रस्तुति के स्लाइड-शो सेटिंग्स को लौटाता है। |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल-पठनीय [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | प्रस्तुति किस प्रारूप से लोड हुई, इस बारे में जानकारी लौटाता है। केवल-पठनीय [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | प्रस्तुति में सभी एंबेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पठनीय [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | प्रस्तुति-व्यापी दृश्य गुणों को प्राप्त करता है। केवल-पठनीय [`IViewProperties`](../iviewproperties). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | प्रस्तुति के सभी स्लाइडों के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | निर्दिष्ट आकार के साथ सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | कस्टम स्केलिंग के साथ सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | नमूना टेक्स्ट के सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | नमूना टेक्स्ट के सभी मेलों को निर्दिष्ट रंग से हाइलाइट करता है। |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | सभी स्लाइडों में सभी स्वीकार्य आकारों के सभी पैराग्राफों में समान स्वरूपण वाले रन को मिलाता है। |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट टेक्स्ट के सभी उदाहरणों को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | प्रस्तुति की सभी स्लाइडों को XAML मार्कअप की फ़ाइलों के सेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | निर्दिष्ट स्लाइडों को पेज संख्या बनाए रखते हुए स्ट्रीम में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | निर्दिष्ट स्लाइडों को पेज संख्या बनाए रखते हुए फ़ाइल में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | निर्दिष्ट स्लाइडों को पेज संख्या बनाए रखते हुए स्ट्रीम में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | निर्दिष्ट स्लाइडों को पेज संख्या बनाए रखते हुए फ़ाइल में निर्दिष्ट फ़ॉर्मेट में सहेजता है। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि PowerPoint Presentation कैसे बनाते हैं।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation())
{
    // पहली स्लाइड प्राप्त करें
    ISlide slide = presentation.Slides[0];
    // लाइन प्रकार का एक ऑटोशेप जोड़ें
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// प्रस्तुति फ़ाइल को सहेजें।
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

निम्न उदाहरण दर्शाता है कि Presentation को कैसे खोलते और सहेजते हैं।

```csharp
[C#]
// Presentation में कोई भी समर्थित फ़ाइल लोड करें, जैसे ppt, pptx, odp आदि.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// प्रस्तुति फ़ाइल सहेजें।
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->