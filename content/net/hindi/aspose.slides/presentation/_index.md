---
title: Presentation
second_title: Aspose.Sildes for .NET API संदर्भ
description: Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।
type: docs
weight: 9610
url: /hi/aspose.slides/presentation/
---
## Presentation क्लास

Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।

```csharp
public sealed class Presentation : IPresentation
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Presentation](presentation#constructor)() | यह कन्स्ट्रक्टर नई प्रस्तुति को शुरुआत से बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_1)(LoadOptions) | यह कन्स्ट्रक्टर नई प्रस्तुति को शुरुआत से बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है। |
| [Presentation](presentation#constructor_2)(Stream) | यह कन्स्ट्रक्टर मौजूदा Presentation को पढ़ने का प्राथमिक तंत्र है। |
| [Presentation](presentation#constructor_4)(string) | यह कन्स्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है, जिससे Presentation की सामग्री पढ़ी जाती है। |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | यह कन्स्ट्रक्टर मौजूदा Presentation को पढ़ने का प्राथमिक तंत्र है। |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | यह कन्स्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है, जिससे Presentation की सामग्री पढ़ी जाती है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | प्रेज़ेंटेशन में सभी कस्टम डेटा भागों को लौटाता है। केवल-पढ़ने योग्य [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | प्रेज़ेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | दिनांक और समय लौटाता या सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। डिफ़ॉल्ट रूप से इस Presentation ऑब्जेक्ट के निर्माण का समय। पढ़ने/लिखने योग्य DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | प्रेज़ेंटेशन का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | आकारों के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | प्रेज़ेंटेशन पर हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम डॉक्यूमेंट प्रॉपर्टी शामिल हैं। केवल-पढ़ने योग्य [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | प्रेज़ेंटेशन में पहली स्लाइड नंबर को दर्शाता है |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | फ़ॉन्ट मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | वास्तविक HeaderFooter मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | सभी प्रेज़ेंटेशन स्लाइडों में मौजूद सभी हाइपरलिंक तक आसान पहुंच प्रदान करता है (मास्टर, लेआउट, नोट्स स्लाइडों में नहीं)। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | प्रेज़ेंटेशन में सभी छवियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | प्रेज़ेंटेशन में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | हैंडआउट मास्टर मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | नोट्स मास्टर मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | प्रेज़ेंटेशन में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | मास्टर थीम लौटाता है। केवल-पढ़ने योग्य [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | इस प्रेज़ेंटेशन के अनुमतियों का मैनेजर प्राप्त करता है। केवल-पढ़ने योग्य [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | प्रेज़ेंटेशन में परिभाषित सभी स्लाइड सेक्शनों की सूची लौटाता है। केवल-पढ़ने योग्य [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | प्रेज़ेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | प्रेज़ेंटेशन में परिभाषित सभी स्लाइडों की सूची लौटाता है। केवल-पढ़ने योग्य [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | प्रेज़ेंटेशन के स्लाइड शो सेटिंग्स लौटाता है। |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | किस प्रारूप से प्रेज़ेंटेशन लोड किया गया, इस बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | प्रेज़ेंटेशन मैक्रो के साथ VBA प्रोजेक्ट प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | प्रेज़ेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | प्रेज़ेंटेशन-व्यापी दृश्य गुण प्राप्त करता है। केवल-पढ़ने योग्य [`IViewProperties`](../iviewproperties). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | इस Presentation ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | एक प्रस्तुति की सभी स्लाइडों के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | कस्टम स्केलिंग के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है। |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | नमूना पाठ के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | नमूना पाठ के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | सभी स्लाइडों में सभी स्वीकार्य आकारों के सभी पैराग्राफों में समान स्वरूप वाले रन को जोड़ता है। |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | प्रेज़ेंटेशन में सभी चार्टों का डेटा उनके स्रोत वर्कबुक्स से पुनः लोड करता है। |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट पाठ की सभी घटनाओं को दूसरी निर्दिष्ट पाठ से बदलता है। |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | प्रेज़ेंटेशन की सभी स्लाइडों को XAML मार्कअप दर्शाने वाली फाइलों के सेट में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | प्रेज़ेंटेशन की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में एक स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | प्रेज़ेंटेशन की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट वाली फाइल में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | प्रेज़ेंटेशन की निर्दिष्ट स्लाइडों को पृष्ठ नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में एक स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | प्रेज़ेंटेशन की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में एक स्ट्रीम पर अतिरिक्त विकल्पों के साथ सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | प्रेज़ेंटेशन की निर्दिष्ट स्लाइडों को पृष्ठ नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट वाली फाइल में सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | प्रेज़ेंटेशन की निर्दिष्ट स्लाइडों को पृष्ठ नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में एक स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | प्रेज़ेंटेशन की निर्दिष्ट स्लाइडों को पृष्ठ नंबर बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट वाली फाइल में सहेजता है। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint Presentation कैसे बनाएं।

```csharp
[C#]
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाएं
using (Presentation presentation = new Presentation())
{
    // पहली स्लाइड प्राप्त करें
    ISlide slide = presentation.Slides[0];
    // लाइन प्रकार की एक ऑटॉशेप जोड़ें
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// प्रस्तुति फ़ाइल सहेजें।
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

निम्न उदाहरण दिखाता है कि Presentation को कैसे खोलें और सहेजें।

```csharp
[C#]
// Presentation में कोई भी समर्थित फ़ाइल को लोड करें, जैसे ppt, pptx, odp आदि।
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// प्रेज़ेंटेशन फ़ाइल सहेजें।
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### देखें

* इंटरफ़ेस [IPresentation](../ipresentation)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->