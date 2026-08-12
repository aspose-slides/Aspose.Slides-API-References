---
title: Presentation
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।
type: docs
weight: 4837
url: /hi/aspose.slides/presentation/
---
## Presentation क्लास

Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## विधियाँ

| Method | Description |
| --- | --- |
| void [Dispose](./dispose/)() override | इस [Presentation](./) वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | मान प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | प्रस्तुति में सभी कस्टम डेटा भाग लौटाता है। केवल-पठन [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में एम्बेडेड ऑडियो फ़ाइल लौटाता है। केवल-पठन [Aspose::Slides::IAudio](../iaudio/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पठन [IAudioCollection](../iaudiocollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर टिप्पणी लेखक लौटाता है। केवल-पठन [Aspose::Slides::ICommentAuthor](../icommentauthor/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | टिप्पणियों के लेखकों का संग्रह लौटाता है। केवल-पठन [ICommentAuthorCollection](../icommentauthorcollection/)। |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | तारीख और समय लौटाता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। यह [Presentation](./) वस्तु निर्माण का समय डिफ़ॉल्ट रूप से है। पढ़ें [System::DateTime](../../system/datetime/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | प्रस्तुति का कस्टम डेटा लौटाता है। केवल-पठन [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली लौटाता है। केवल-पठन [ITextStyle](../itextstyle/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति को साइन करने के लिए उपयोग किया गया डिजिटल हस्ताक्षर लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | प्रस्तुति को साइन करने के लिए उपयोग किए गए हस्ताक्षरों का संग्रह लौटाता है। केवल-पठन [IDigitalSignatureCollection](../idigitalsignaturecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | [DocumentProperties](../documentproperties/) वस्तु लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं। केवल-पठन [IDocumentProperties](../idocumentproperties/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | नाम द्वारा परिभाषित कस्टम प्रॉपर्टी लौटाता है। |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | प्रस्तुति में पहली स्लाइड संख्या दर्शाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | फ़ॉन्ट मैनेजर लौटाता है। केवल-पठन [IFontsManager](../ifontsmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | वास्तविक HeaderFooter मैनेजर लौटाता है। केवल-पठन [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | सभी प्रस्तुति स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं) में मौजूद सभी हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पठन [IHyperlinkQueries](../ihyperlinkqueries/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में छवि लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | प्रस्तुति में सभी छवियों का संग्रह लौटाता है। केवल-पठन [IImageCollection](../iimagecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | अनुक्रमांक द्वारा लेआउट स्लाइड लौटाता है। केवल-पठन [Aspose::Slides::ILayoutSlide](../ilayoutslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | प्रस्तुति में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है। केवल-पठन [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में परिभाषित एक मास्टर स्लाइड लौटाता है। केवल-पठन [Aspose::Slides::IMasterSlide](../imasterslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | हैंडआउट मास्टर मैनेजर लौटाता है। केवल-पठन [IMasterHandoutSlideManager](../imasterhandoutslidemanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | नोट्स मास्टर मैनेजर लौटाता है। केवल-पठन [IMasterNotesSlideManager](../imasternotesslidemanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | प्रस्तुति में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है। केवल-पठन [IMasterSlideCollection](../imasterslidecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | मास्टर थीम लौटाता है। केवल-पठन [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | नोट्स स्लाइड आकार वस्तु लौटाता है। केवल-पठन [INotesSize](../inotessize/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | इस प्रस्तुति के अधिकारों के मैनेजर को प्राप्त करता है। केवल-पठन [IProtectionManager](../iprotectionmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में परिभाषित एक स्लाइड सेक्शन लौटाता है। केवल-पठन [Aspose::Slides::ISection](../isection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | प्रस्तुति में परिभाषित सभी स्लाइड सेक्शनों की सूची लौटाता है। केवल-पठन [ISectionCollection](../isectioncollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल्स का संग्रह लौटाता है। केवल-पठन [ISensitivityLabelCollection](../isensitivitylabelcollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में परिभाषित एक स्लाइड लौटाता है। केवल-पठन [Aspose::Slides::ISlide](../islide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | प्रस्तुति में परिभाषित सभी स्लाइड्स की सूची लौटाता है। केवल-पठन [ISlideCollection](../islidecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | प्रस्तुति के स्लाइड शो सेटिंग्स लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | स्लाइड आकार वस्तु लौटाता है। केवल-पठन [ISlideSize](../islidesize/)। |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | किस प्रारूप से प्रस्तुति लोड की गई, इसकी जानकारी लौटाता है। केवल-पठन [SourceFormat](../sourceformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट प्राप्त करता है। पढ़ें [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर प्रस्तुति में एम्बेडेड वीडियो फ़ाइल लौटाता है। केवल-पठन [Aspose::Slides::IVideo](../ivideo/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पठन [IVideoCollection](../ivideocollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | प्रस्तुति-व्यापी दृश्य गुण प्राप्त करता है। केवल-पठन [IViewProperties](../iviewproperties/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का C# समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | प्रस्तुति के सभी स्लाइड्स के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | प्रस्तुति के निर्दिष्ट स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | कस्टम स्केलिंग के साथ प्रस्तुति के सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | कस्टम स्केलिंग के साथ प्रस्तुति के निर्दिष्ट स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | निर्दिष्ट आकार के साथ प्रस्तुति के सभी स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | निर्दिष्ट आकार के साथ प्रस्तुति के निर्दिष्ट स्लाइड्स के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | Id द्वारा [Slide](../slide/), [MasterSlide](../masterslide/) या [LayoutSlide](../layoutslide/) लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है। |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | नमूना पाठ के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है। |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | नमूना पाठ के सभी मिलानों को निर्दिष्ट रंग से हाइलाइट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | सभी स्लाइड्स में सभी स्वीकार्य शेप्स के सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
|  [Presentation](./presentation/)() | यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है। |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | यह कंस्ट्रक्टर नई प्रस्तुति को शून्य से बनाता है। बनाई गई प्रस्तुति में एक खाली स्लाइड होती है। |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | यह कंस्ट्रक्टर मौजूदा [Presentation](./) को पढ़ने का मुख्य तंत्र है। |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | यह कंस्ट्रक्टर मौजूदा [Presentation](./) को पढ़ने का मुख्य तंत्र है। |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे [Presentation](./) की सामग्री पढ़ी जाती है। |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे [Presentation](./) की सामग्री पढ़ी जाती है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है। |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | निर्दिष्ट पाठ की सभी घटनाओं को दूसरे निर्दिष्ट पाठ से बदलता है। |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में एक स्ट्रीम में सहेजता है। |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है। |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है। |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है। |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या संरक्षित रखते हुए निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या संरक्षित रखते हुए निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है। |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या संरक्षित रखते हुए निर्दिष्ट प्रारूप में एक स्ट्रीम में सहेजता है। |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या संरक्षित रखते हुए निर्दिष्ट प्रारूप में एक स्ट्रीम में सहेजता है। |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | तारीख और समय सेट करता है जो datetime फ़ील्ड की सामग्री को प्रतिस्थापित करेगा। यह [Presentation](./) वस्तु का निर्माण समय डिफ़ॉल्ट है। लिखें [System::DateTime](../../system/datetime/)। |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | नाम द्वारा परिभाषित कस्टम प्रॉपर्टी सेट करता है। |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | प्रस्तुति में पहली स्लाइड संख्या दर्शाता है। |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | प्रस्तुति मैक्रो के साथ VBA प्रोजेक्ट सेट करता है। लिखें [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने की सुविधा देता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](./) कैसे बनाएं।  
```cpp
// प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाता है
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// पहली स्लाइड प्राप्त करें
auto slide = presentation->get_Slides()->idx_get(0);
// लाइन प्रकार की एक ऑटोशेप जोड़ें
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// प्रस्तुति फ़ाइल को सहेजें।
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दिखाता है कि [Presentation](./) को कैसे खोलें और सहेजें।  
```cpp
// Presentation में कोई भी समर्थित फ़ाइल लोड करें, जैसे ppt, pptx, odp आदि।
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// प्रस्तुति फ़ाइल को सहेजें।
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## देखें भी

* क्लास [IPresentation](../ipresentation/)
* क्लास [IDOMObject](../idomobject/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)