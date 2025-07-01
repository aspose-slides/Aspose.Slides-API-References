---
title: IPresentation
second_title: Aspose.Sildes for .NET API Reference
description: Presentation document
type: docs
weight: 6610
url: /aspose.slides/ipresentation/
---

## IPresentation interface

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Returns all custom data parts in the presentaion. Read-only [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Returns IDisposable interface. Read-only IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Returns the collection of all embedded audio files in the presentation. Read-only [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Returns the collection of comments autors. Read-only [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Returns the presentation's custom data. Read-only [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Returns default text style for shapes. Read-only [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Returns the collection of signatures used to sign the presentation. Read-only [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Returns DocumentProperties object which contains standard and custom document properties. Read-only [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Represents the first slide number in the presentation. Read/write Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Returns fonts manager. Read-only [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Returns HeaderFooter manager of the presentation. Read-only [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Returns the collection of all images in the presentation. Read-only [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Returns a list of all layout slides that are defined in the presentation. Read-only [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Returns handout master manager. Read-only [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Returns notes master manager. Read-only [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Returns a list of all master slides that are defined in the presentation. Read-only [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Returns master theme of the presentation. Read-only [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Returns notes slide size object. Read-only [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Gets manager of the permissions for this presentation. Read-only [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Returns a list of all slides sections that are defined in the presentation. Read-only [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Returns a list of all slides that are defined in the presentation. Read-only [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Returns slide size object. Read-only [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Returns information about from which format presentation was loaded. Read-only [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Gets VBA project with presentation macros. Read/write [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Returns the collection of all embedded video files in the presentation. Read-only [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Gets presentation wide view properties. Read-only [`IViewProperties`](../iviewproperties). |

## Methods

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Highlights all matches of the regular expression with the specified color. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Highlights all matches of the sample text with the specified color. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Highlights all matches of the sample text with the specified color. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Replaces all matches of the regular expression with the specified string. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Replaces all occurrences of the specified text with another specified text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Saves all slides of a presentation to a stream in the specified format. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Saves all slides of a presentation to a file with the specified format. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Saves specified slides of a presentation to a stream in the specified format. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Saves specified slides of a presentation to a file with the specified format. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a file with the specified format. |

### See Also

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
