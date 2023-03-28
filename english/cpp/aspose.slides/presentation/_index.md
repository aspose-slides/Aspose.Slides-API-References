---
title: Presentation
second_title: Aspose.Slides for C++ API Reference
description: Represents a Microsoft PowerPoint presentation.
type: docs
weight: 4603
url: /cpp/aspose.slides/presentation/
---
## Presentation class


Represents a Microsoft PowerPoint presentation.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## Methods

| Method | Description |
| --- | --- |
| void [Dispose](./dispose/)() override | Releases all resources used by this [Presentation](./) object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | Returns all custom data parts in the presentaion. Read-only [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | Return embedded audio file in the presentation at the specified index. Read-only [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | Returns the collection of all embedded audio files in the presentation. Read-only [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | Returns the comment author at the specified index. Read-only [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | Returns the collection of comments autors. Read-only [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | Returns date and time which will substitute content of datetime fields. Time of this [Presentation](./) object creation by default. Read [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Returns the presentation's custom data. Read-only [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | Returns default text style for shapes. Read-only [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | Returns digital signature used to sign the presentation at the specified index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | Returns the collection of signatures used to sign the presentation. Read-only [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | Returns [DocumentProperties](../documentproperties/) object which contains standard and custom document properties. Read-only [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | Returns custom property defined by name. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | Represents the first slide number in the presentation |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | Returns fonts manager. Read-only [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Returns actual HeaderFooter manager. Read-only [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | Returns image in the presentation at the specified index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | Returns the collection of all images in the presentation. Read-only [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Returns a list of all layout slides that are defined in the presentation. Read-only [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | Returns a master slide defined in the presentation at the specified index. Read-only [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | Returns handout master manager. Read-only [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | Returns notes master manager. Read-only [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | Returns a list of all master slides that are defined in the presentation. Read-only [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | Returns master theme. Read-only [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | Returns notes slide size object. Read-only [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | Gets manager of the permissions for this presentation. Read-only [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | Returns a slide section defined in the presentation at the specified index. Read-only [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | Returns a list of all slides sections that are defined in the presentation. Read-only [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | Returns a slide defined in the presentation at the specified index. Read-only [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | Returns the slide show settings for the presentation. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | Returns slide size object. Read-only [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | Returns information about from which format presentation was loaded. Read-only [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | Gets VBA project with presentation macros. Read [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | Return embedded video file in the presentation at the specified index. Read-only [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | Returns the collection of all embedded video files in the presentation. Read-only [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | Gets presentation wide view properties. Read-only [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | Returns a [Slide](../slide/), [MasterSlide](../masterslide/) or [LayoutSlide](../layoutslide/) by Id. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>) override | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>, **float**, **float**) override | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../aspose.slides.export/inotescommentslayoutingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\>\> [GetThumbnails](./getthumbnails/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
|  [Presentation](./presentation/)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | This constructor is the primary mechanism for reading an existing [Presentation](./). |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | This constructor is the primary mechanism for reading an existing [Presentation](./). |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | This constructor gets a source file path from which the contents of the [Presentation](./) are read. |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | This constructor gets a source file path from which the contents of the [Presentation](./) are read. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Saves all slides of a presentation to a file with the specified format. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Saves all slides of a presentation to a stream in the specified format. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Saves all slides of a presentation to a file with the specified format and with additional options. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | Saves all slides of a presentation to a set of files representing XAML markup. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[System::Web::HttpResponse](../../system.web/httpresponse/)\>, **bool**) override | Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Web::HttpResponse](../../system.web/httpresponse/)\>, **bool**) override | Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | Sets date and time which will substitute content of datetime fields. Time of this [Presentation](./) object creation by default. Write [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Set custom property defined by name. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | Represents the first slide number in the presentation |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | Sets VBA project with presentation macros. Write [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Remarks


The following example shows how to create PowerPoint [Presentation](./). 
```cpp
// Instantiate a Presentation object that represents a presentation file
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// Get the first slide
auto slide = presentation->get_Slides()->idx_get(0);
// Add an autoshape of type line
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// Save the presentation file.
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to open and save [Presentation](./). 
```cpp
// Load any supported file in Presentation e.g. ppt, pptx, odp etc.
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// Save the presentation file.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## See Also

* Class [IPresentation](../ipresentation/)
* Class [IDOMObject](../idomobject/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)
