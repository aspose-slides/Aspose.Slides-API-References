---
title: IPresentation
second_title: Aspose.Sildes for .NET API संदर्भ
description: प्रस्तुति दस्तावेज़
type: docs
weight: 6750
url: /hi/aspose.slides/ipresentation/
---
## IPresentation इंटरफ़ेस

प्रस्तुति दस्तावेज़

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | प्रस्तुति में सभी कस्टम डेटा भागों को लौटाता है। केवल-पढ़ने योग्य [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य IDisposable। |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | प्रस्तुति में सभी सम्मिलित ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAudioCollection`](../iaudiocollection)। |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`ICommentAuthorCollection`](../icommentauthorcollection)। |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | डेट/समय (DateTime) लौटाता या सेट करता है जो datetime फ़ील्डों की सामग्री को प्रतिस्थापित करेगा। डिफ़ॉल्ट रूप से इस Presentation वस्तु के निर्माण का समय। पढ़ने/लिखने योग्य DateTime। |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | प्रस्तुति का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle)। |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | प्रस्तुति पर हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IDigitalSignatureCollection`](../idigitalsignaturecollection)। |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल-पढ़ने योग्य [`IDocumentProperties`](../idocumentproperties)। |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | प्रस्तुति में पहला स्लाइड नंबर दर्शाता है। पढ़ने/लिखने योग्य Int32। |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | फ़ॉन्ट्स प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IFontsManager`](../ifontsmanager)। |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | प्रस्तुति के HeaderFooter प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)। |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | सभी प्रस्तुति स्लाइड्स में (मास्टर, लेआउट, नोट्स स्लाइड्स नहीं) मौजूद सभी हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [Images](../../aspose.slides/ipresentation/images) { get; } | प्रस्तुति में सभी छवियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IImageCollection`](../iimagecollection)। |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | प्रस्तुति में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)। |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | हैंडआउट मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)। |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | नोट्स मास्टर प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IMasterNotesSlideManager`](../imasternotesslidemanager)। |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | प्रस्तुति में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`IMasterSlideCollection`](../imasterslidecollection)। |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | प्रस्तुति का मास्टर थीम लौटाता है। केवल-पढ़ने योग्य [`IMasterTheme`](../../aspose.slides.theme/imastertheme)। |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | नोट्स स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`INotesSize`](../inotessize)। |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | इस प्रस्तुति के अनुमतियों के प्रबंधक को प्राप्त करता है। केवल-पढ़ने योग्य [`IProtectionManager`](../iprotectionmanager)। |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | प्रस्तुति में परिभाषित सभी स्लाइड सेक्शनों की सूची लौटाता है। केवल-पढ़ने योग्य [`ISectionCollection`](../isectioncollection)। |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [`ISensitivityLabelCollection`](../isensitivitylabelcollection)। |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | प्रस्तुति में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`ISlideCollection`](../islidecollection)। |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`ISlideSize`](../islidesize)। |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | प्रस्तुति किस प्रारूप से लोड किया गया, इस बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [`SourceFormat`](./sourceformat)। |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | प्रस्तुति मैक्रोज़ के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ने/लिखने योग्य [`IVbaProject`](../../aspose.slides.vba/ivbaproject)। |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | प्रस्तुति में सभी सम्मिलित वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IVideoCollection`](../ivideocollection)। |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | प्रस्तुति व्यापक दृश्य गुण प्राप्त करता है। केवल-पढ़ने योग्य [`IViewProperties`](../iviewproperties)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | एक प्रस्तुति की सभी स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स के लिए Thumbnail Bitmap ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | एक प्रस्तुति की सभी स्लाइड्स के लिए निर्दिष्ट आकार के साथ Thumbnail Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | एक प्रस्तुति की सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ Thumbnail Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स के लिए निर्दिष्ट आकार के साथ Thumbnail Image ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स के लिए कस्टम स्केलिंग के साथ Thumbnail Image ऑब्जेक्ट्स लौटाता है। |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Id द्वारा एक Slide, MasterSlide या LayoutSlide लौटाता है। |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलानों को हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलानों को हाईलाइट करता है। |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | सभी स्लाइड्स में सभी स्वीकार्य शैलियों में सभी पैराग्राफों में समान स्वरूप के रन को जोड़ता है। |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मिलानों को निर्धारित स्ट्रिंग से बदलता है। |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | निर्धारित पाठ की सभी घटनाओं को अन्य निर्धारित पाठ से बदलता है। |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | एक प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में और अतिरिक्त विकल्पों के साथ स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम पर सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |

### देखें

* इंटरफ़ेस [IPresentationComponent](../ipresentationcomponent)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->