---
title: IPresentation
second_title: Aspose.Sildes for .NET API संदर्भ
description: प्रेजेंटेशन दस्तावेज़
type: docs
weight: 6750
url: /hi/aspose.slides/ipresentation/
---
## IPresentation इंटरफ़ेस

प्रेजेंटेशन दस्तावेज़

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | प्रेजेंटेशन में सभी कस्टम डेटा भागों को लौटाता है। केवल-पढ़ने योग्य [`ICustomXmlPart`](../icustomxmlpart)[]। |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable इंटरफ़ेस को लौटाता है। केवल-पढ़ने योग्य IDisposable। |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | प्रेजेंटेशन में सभी एम्बेडेड ऑडियो फ़ाइलों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`IAudioCollection`](../iaudiocollection)। |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | टिप्पणी लेखकों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`ICommentAuthorCollection`](../icommentauthorcollection)। |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | डेटाटाइम फ़ील्ड की सामग्री को प्रतिस्थापित करने वाली तिथि और समय को लौटाता या सेट करता है। यह प्रेजेंटेशन ऑब्जेक्ट के निर्माण का समय डिफ़ॉल्ट रूप से होता है। पढ़ने/लिखने योग्य DateTime। |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | प्रेजेंटेशन का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट स्टाइल लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle)। |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | प्रेजेंटेशन पर साइन करने के लिए उपयोग किए गए हस्ताक्षरों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`IDigitalSignatureCollection`](../idigitalsignaturecollection)। |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | DocumentProperties ऑब्जेक्ट लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण सम्मिलित हैं। केवल-पढ़ने योग्य [`IDocumentProperties`](../idocumentproperties)। |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | प्रेजेंटेशन में प्रथम स्लाइड संख्या को दर्शाता है। पढ़ने/लिखने योग्य Int32। |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | फ़ॉन्ट्स मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IFontsManager`](../ifontsmanager)। |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | प्रेजेंटेशन के HeaderFooter मैनेजर को लौटाता है। केवल-पढ़ने योग्य [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)। |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | सभी प्रेजेंटेशन स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं) में स्थित सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [Images](../../aspose.slides/ipresentation/images) { get; } | प्रेजेंटेशन में सभी छवियों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`IImageCollection`](../iimagecollection)। |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | प्रेजेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)। |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | हैंडआउट मास्टर मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)। |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | नोट्स मास्टर मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterNotesSlideManager`](../imasternotesslidemanager)। |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`IMasterSlideCollection`](../imasterslidecollection)। |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | प्रेजेंटेशन की मास्टर थीम को लौटाता है। केवल-पढ़ने योग्य [`IMasterTheme`](../../aspose.slides.theme/imastertheme)। |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | नोट्स स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`INotesSize`](../inotessize)। |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | इस प्रेजेंटेशन के अनुमतियों के मैनेजर को प्राप्त करता है। केवल-पढ़ने योग्य [`IProtectionManager`](../iprotectionmanager)। |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | प्रेजेंटेशन में परिभाषित सभी स्लाइड सेक्शन्स की सूची लौटाता है। केवल-पढ़ने योग्य [`ISectionCollection`](../isectioncollection)। |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`ISensitivityLabelCollection`](../isensitivitylabelcollection)। |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | प्रेजेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल-पढ़ने योग्य [`ISlideCollection`](../islidecollection)। |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | स्लाइड आकार ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`ISlideSize`](../islidesize)। |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | प्रेजेंटेशन किस प्रारूप से लोड किया गया, इस संबंध में जानकारी लौटाता है। केवल-पढ़ने योग्य [`SourceFormat`](./sourceformat)। |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | प्रेजेंटेशन मैक्रोज़ वाला VBA प्रोजेक्ट प्राप्त करता है। पढ़ने/लिखने योग्य [`IVbaProject`](../../aspose.slides.vba/ivbaproject)। |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | प्रेजेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`IVideoCollection`](../ivideocollection)। |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | प्रेजेंटेशन-व्यापी दृश्य गुण प्राप्त करता है। केवल-पढ़ने योग्य [`IViewProperties`](../iviewproperties)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | प्रेजेंटेशन के सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | निर्दिष्ट स्लाइड्स के लिए थंबनेल बिटमैप ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | निर्दिष्ट आकार के साथ प्रेजेंटेशन के सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | कस्टम स्केलिंग के साथ प्रेजेंटेशन के सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है। |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मेल को निर्दिष्ट रंग से हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | नमूना टेक्स्ट के सभी मेल को निर्दिष्ट रंग से हाईलाइट करता है। |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | नमूना टेक्स्ट के सभी मेल को निर्दिष्ट रंग से हाईलाइट करता है। |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | सभी स्लाइड्स में सभी स्वीकार्य शेप्स के सभी पैराग्राफ़ में समान फॉर्मेटिंग वाले रन्स को जोड़ता है। |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | नियमित अभिव्यक्ति के सभी मेल को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | प्रेजेंटेशन की सभी स्लाइड्स को XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की सभी स्लाइड्स को एक स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को एक स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को एक स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ प्रेजेंटेशन की सभी स्लाइड्स को फ़ाइल में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | निर्दिष्ट फ़ॉर्मेट में प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को एक स्ट्रीम में सहेजता है। |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | निर्दिष्ट फ़ॉर्मेट के साथ प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को फ़ाइल में सहेजता है। |

### देखें

* इंटरफ़ेस [IPresentationComponent](../ipresentationcomponent)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->